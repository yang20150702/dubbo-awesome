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
# Warmup Iteration   1: 4.405 ops/ms
# Warmup Iteration   2: 8.879 ops/ms
# Warmup Iteration   3: 9.810 ops/ms
Iteration   1: 10.509 ops/ms
Iteration   2: 10.604 ops/ms
Iteration   3: 10.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.499 ±(99.9%) 2.024 ops/ms [Average]
  (min, avg, max) = (10.383, 10.499, 10.604), stdev = 0.111
  CI (99.9%): [8.475, 12.522] (assumes normal distribution)


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
# Warmup Iteration   1: 7.309 ops/ms
# Warmup Iteration   2: 10.341 ops/ms
# Warmup Iteration   3: 10.949 ops/ms
Iteration   1: 10.802 ops/ms
Iteration   2: 10.875 ops/ms
Iteration   3: 10.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.861 ±(99.9%) 0.974 ops/ms [Average]
  (min, avg, max) = (10.802, 10.861, 10.906), stdev = 0.053
  CI (99.9%): [9.887, 11.835] (assumes normal distribution)


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
# Warmup Iteration   1: 7.255 ops/ms
# Warmup Iteration   2: 10.075 ops/ms
# Warmup Iteration   3: 10.343 ops/ms
Iteration   1: 10.477 ops/ms
Iteration   2: 10.448 ops/ms
Iteration   3: 10.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.455 ±(99.9%) 0.360 ops/ms [Average]
  (min, avg, max) = (10.440, 10.455, 10.477), stdev = 0.020
  CI (99.9%): [10.095, 10.815] (assumes normal distribution)


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
# Warmup Iteration   1: 5.630 ops/ms
# Warmup Iteration   2: 7.999 ops/ms
# Warmup Iteration   3: 7.996 ops/ms
Iteration   1: 8.163 ops/ms
Iteration   2: 8.312 ops/ms
Iteration   3: 8.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.245 ±(99.9%) 1.378 ops/ms [Average]
  (min, avg, max) = (8.163, 8.245, 8.312), stdev = 0.076
  CI (99.9%): [6.867, 9.622] (assumes normal distribution)


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.004 ms/op
Iteration   1: 3.077 ±(99.9%) 0.003 ms/op
Iteration   2: 3.137 ±(99.9%) 0.005 ms/op
Iteration   3: 3.056 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.090 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (3.056, 3.090, 3.137), stdev = 0.042
  CI (99.9%): [2.328, 3.852] (assumes normal distribution)


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
# Warmup Iteration   1: 3.910 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.003 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
Iteration   2: 2.957 ±(99.9%) 0.003 ms/op
Iteration   3: 2.932 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.958 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (2.932, 2.958, 2.987), stdev = 0.027
  CI (99.9%): [2.459, 3.458] (assumes normal distribution)


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
# Warmup Iteration   1: 4.240 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.002 ms/op
Iteration   1: 3.168 ±(99.9%) 0.002 ms/op
Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
Iteration   3: 3.078 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.125 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (3.078, 3.125, 3.168), stdev = 0.045
  CI (99.9%): [2.296, 3.953] (assumes normal distribution)


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
# Warmup Iteration   1: 5.075 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.044 ms/op
Iteration   1: 3.834 ±(99.9%) 0.009 ms/op
Iteration   2: 3.896 ±(99.9%) 0.037 ms/op
Iteration   3: 3.871 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.867 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (3.834, 3.867, 3.896), stdev = 0.031
  CI (99.9%): [3.299, 4.434] (assumes normal distribution)


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
Iteration   1: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  9.499 ms/op
                 createUser·p0.9999: 12.200 ms/op
                 createUser·p1.00:   15.155 ms/op

Iteration   2: 3.162 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.499 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  9.222 ms/op
                 createUser·p0.9999: 15.133 ms/op
                 createUser·p1.00:   15.483 ms/op

Iteration   3: 3.065 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.485 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  14.094 ms/op
                 createUser·p0.9999: 23.906 ms/op
                 createUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309184
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15077 
    [ 2.500,  5.000) = 292041 
    [ 5.000,  7.500) = 1541 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      9.841 ms/op
     p(99.9900) =     23.661 ms/op
     p(99.9990) =     24.947 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
Iteration   1: 2.921 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  9.625 ms/op
                 existUser·p0.9999: 25.264 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  8.585 ms/op
                 existUser·p0.9999: 14.683 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  9.732 ms/op
                 existUser·p0.9999: 16.451 ms/op
                 existUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326724
  mean =      2.939 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35503 
    [ 2.500,  5.000) = 289542 
    [ 5.000,  7.500) = 1178 
    [ 7.500, 10.000) = 255 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.180 ms/op
     p(99.9900) =     16.548 ms/op
     p(99.9990) =     25.410 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  13.566 ms/op
                 getUser·p0.9999: 15.204 ms/op
                 getUser·p1.00:   15.417 ms/op

Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.586 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.465 ms/op
                 getUser·p0.9999: 16.527 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.582 ms/op
                 getUser·p0.9999: 17.458 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308555
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1050 
    [ 1.250,  2.500) = 14020 
    [ 2.500,  3.750) = 268566 
    [ 3.750,  5.000) = 23257 
    [ 5.000,  6.250) = 773 
    [ 6.250,  7.500) = 402 
    [ 7.500,  8.750) = 175 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 70 
    [15.000, 16.250) = 76 
    [16.250, 17.500) = 71 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.822 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     17.725 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 5.255 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.011 ms/op
Iteration   1: 3.863 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.391 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  12.406 ms/op
                 listUser·p0.9999: 14.292 ms/op
                 listUser·p1.00:   15.696 ms/op

Iteration   2: 3.823 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.490 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  14.059 ms/op
                 listUser·p0.9999: 18.961 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   3: 3.936 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 21.623 ms/op
                 listUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247647
  mean =      3.873 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2932 
    [ 2.500,  5.000) = 229149 
    [ 5.000,  7.500) = 14589 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     21.906 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.499 ± 2.024  ops/ms
ClientGrpc.existUser                       thrpt       3  10.861 ± 0.974  ops/ms
ClientGrpc.getUser                         thrpt       3  10.455 ± 0.360  ops/ms
ClientGrpc.listUser                        thrpt       3   8.245 ± 1.378  ops/ms
ClientGrpc.createUser                       avgt       3   3.090 ± 0.762   ms/op
ClientGrpc.existUser                        avgt       3   2.958 ± 0.500   ms/op
ClientGrpc.getUser                          avgt       3   3.125 ± 0.828   ms/op
ClientGrpc.listUser                         avgt       3   3.867 ± 0.568   ms/op
ClientGrpc.createUser                     sample  309184   3.105 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.485           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.841           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.661           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.297           ms/op
ClientGrpc.existUser                      sample  326724   2.939 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.628           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.180           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.548           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.526           ms/op
ClientGrpc.getUser                        sample  308555   3.110 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.586           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.822           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.105           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.859           ms/op
ClientGrpc.listUser                       sample  247647   3.873 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.391           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.375           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.259           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.386           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.431           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.593           ms/op
