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
# Warmup Iteration   1: 2.453 ops/ms
# Warmup Iteration   2: 5.342 ops/ms
# Warmup Iteration   3: 7.207 ops/ms
Iteration   1: 7.419 ops/ms
Iteration   2: 7.529 ops/ms
Iteration   3: 7.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.624 ±(99.9%) 4.838 ops/ms [Average]
  (min, avg, max) = (7.419, 7.624, 7.923), stdev = 0.265
  CI (99.9%): [2.785, 12.462] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.987 ops/ms
# Warmup Iteration   2: 7.541 ops/ms
# Warmup Iteration   3: 7.883 ops/ms
Iteration   1: 8.197 ops/ms
Iteration   2: 8.620 ops/ms
Iteration   3: 8.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.444 ±(99.9%) 4.009 ops/ms [Average]
  (min, avg, max) = (8.197, 8.444, 8.620), stdev = 0.220
  CI (99.9%): [4.435, 12.452] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.591 ops/ms
# Warmup Iteration   2: 7.078 ops/ms
# Warmup Iteration   3: 7.445 ops/ms
Iteration   1: 7.955 ops/ms
Iteration   2: 7.991 ops/ms
Iteration   3: 8.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.034 ±(99.9%) 1.956 ops/ms [Average]
  (min, avg, max) = (7.955, 8.034, 8.156), stdev = 0.107
  CI (99.9%): [6.078, 9.990] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.695 ops/ms
# Warmup Iteration   2: 5.361 ops/ms
# Warmup Iteration   3: 5.997 ops/ms
Iteration   1: 5.727 ops/ms
Iteration   2: 6.225 ops/ms
Iteration   3: 6.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.076 ±(99.9%) 5.534 ops/ms [Average]
  (min, avg, max) = (5.727, 6.076, 6.276), stdev = 0.303
  CI (99.9%): [0.542, 11.609] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.794 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.480 ±(99.9%) 0.009 ms/op
Iteration   1: 4.356 ±(99.9%) 0.004 ms/op
Iteration   2: 4.425 ±(99.9%) 0.003 ms/op
Iteration   3: 4.381 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.387 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (4.356, 4.387, 4.425), stdev = 0.035
  CI (99.9%): [3.753, 5.022] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.760 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.002 ms/op
Iteration   1: 3.746 ±(99.9%) 0.005 ms/op
Iteration   2: 3.991 ±(99.9%) 0.003 ms/op
Iteration   3: 4.040 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.926 ±(99.9%) 2.867 ms/op [Average]
  (min, avg, max) = (3.746, 3.926, 4.040), stdev = 0.157
  CI (99.9%): [1.059, 6.792] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.948 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.005 ms/op
Iteration   1: 4.050 ±(99.9%) 0.003 ms/op
Iteration   2: 4.048 ±(99.9%) 0.003 ms/op
Iteration   3: 4.276 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.124 ±(99.9%) 2.387 ms/op [Average]
  (min, avg, max) = (4.048, 4.124, 4.276), stdev = 0.131
  CI (99.9%): [1.738, 6.511] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.720 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.561 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.334 ±(99.9%) 0.021 ms/op
Iteration   1: 5.430 ±(99.9%) 0.032 ms/op
Iteration   2: 5.439 ±(99.9%) 0.017 ms/op
Iteration   3: 5.354 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.408 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (5.354, 5.408, 5.439), stdev = 0.047
  CI (99.9%): [4.550, 6.265] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.317 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.252 ±(99.9%) 0.014 ms/op
Iteration   1: 4.187 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   4.071 ms/op
                 createUser·p0.90:   5.292 ms/op
                 createUser·p0.95:   5.784 ms/op
                 createUser·p0.99:   8.233 ms/op
                 createUser·p0.999:  10.898 ms/op
                 createUser·p0.9999: 21.093 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   2: 4.655 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   4.465 ms/op
                 createUser·p0.90:   5.915 ms/op
                 createUser·p0.95:   6.545 ms/op
                 createUser·p0.99:   8.648 ms/op
                 createUser·p0.999:  19.968 ms/op
                 createUser·p0.9999: 28.844 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   3: 4.264 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   7.766 ms/op
                 createUser·p0.999:  11.681 ms/op
                 createUser·p0.9999: 23.642 ms/op
                 createUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 220230
  mean =      4.359 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3596 
    [ 2.500,  5.000) = 171636 
    [ 5.000,  7.500) = 41551 
    [ 7.500, 10.000) = 2756 
    [10.000, 12.500) = 432 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.139 ms/op
     p(99.0000) =      8.176 ms/op
     p(99.9000) =     13.726 ms/op
     p(99.9900) =     26.474 ms/op
     p(99.9990) =     29.176 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.220 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.192 ±(99.9%) 0.014 ms/op
Iteration   1: 3.878 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   7.741 ms/op
                 existUser·p0.999:  13.689 ms/op
                 existUser·p0.9999: 17.882 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   2: 3.813 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   7.065 ms/op
                 existUser·p0.999:  11.928 ms/op
                 existUser·p0.9999: 19.446 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   3: 3.924 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   6.684 ms/op
                 existUser·p0.999:  12.361 ms/op
                 existUser·p0.9999: 33.817 ms/op
                 existUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 247943
  mean =      3.872 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14434 
    [ 2.500,  5.000) = 212462 
    [ 5.000,  7.500) = 19010 
    [ 7.500, 10.000) = 1449 
    [10.000, 12.500) = 359 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     12.323 ms/op
     p(99.9900) =     33.201 ms/op
     p(99.9990) =     34.047 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.056 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.220 ±(99.9%) 0.012 ms/op
Iteration   1: 4.435 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.554 ms/op
                 getUser·p0.95:   6.046 ms/op
                 getUser·p0.99:   8.380 ms/op
                 getUser·p0.999:  13.038 ms/op
                 getUser·p0.9999: 15.410 ms/op
                 getUser·p1.00:   15.925 ms/op

Iteration   2: 4.176 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   4.063 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.710 ms/op
                 getUser·p0.99:   7.332 ms/op
                 getUser·p0.999:  11.338 ms/op
                 getUser·p0.9999: 16.466 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   3: 4.071 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   5.136 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  11.409 ms/op
                 getUser·p0.9999: 27.165 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227322
  mean =      4.222 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5275 
    [ 2.500,  5.000) = 186357 
    [ 5.000,  7.500) = 33246 
    [ 7.500, 10.000) = 1798 
    [10.000, 12.500) = 433 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     12.026 ms/op
     p(99.9900) =     26.003 ms/op
     p(99.9990) =     27.531 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 8.105 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.924 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.597 ±(99.9%) 0.024 ms/op
Iteration   1: 5.468 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   7.660 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   10.930 ms/op
                 listUser·p0.999:  17.761 ms/op
                 listUser·p0.9999: 20.197 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 5.573 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.636 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   11.391 ms/op
                 listUser·p0.999:  19.931 ms/op
                 listUser·p0.9999: 27.829 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   3: 5.529 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   10.797 ms/op
                 listUser·p0.999:  22.184 ms/op
                 listUser·p0.9999: 33.148 ms/op
                 listUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173846
  mean =      5.523 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 455 
    [ 2.500,  5.000) = 77622 
    [ 5.000,  7.500) = 74926 
    [ 7.500, 10.000) = 17380 
    [10.000, 12.500) = 2591 
    [12.500, 15.000) = 509 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      7.782 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     32.670 ms/op
     p(99.9990) =     35.882 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.624 ± 4.838  ops/ms
ClientGrpc.existUser                       thrpt       3   8.444 ± 4.009  ops/ms
ClientGrpc.getUser                         thrpt       3   8.034 ± 1.956  ops/ms
ClientGrpc.listUser                        thrpt       3   6.076 ± 5.534  ops/ms
ClientGrpc.createUser                       avgt       3   4.387 ± 0.634   ms/op
ClientGrpc.existUser                        avgt       3   3.926 ± 2.867   ms/op
ClientGrpc.getUser                          avgt       3   4.124 ± 2.387   ms/op
ClientGrpc.listUser                         avgt       3   5.408 ± 0.857   ms/op
ClientGrpc.createUser                     sample  220230   4.359 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.029           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.571           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.139           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.176           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.726           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.474           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.327           ms/op
ClientGrpc.existUser                      sample  247943   3.872 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.926           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.882           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.415           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.176           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.323           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.201           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.144           ms/op
ClientGrpc.getUser                        sample  227322   4.222 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.994           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.096           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.816           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.660           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.026           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.003           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.623           ms/op
ClientGrpc.listUser                       sample  173846   5.523 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.487           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.782           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.765           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.059           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.809           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.670           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.979           ms/op
