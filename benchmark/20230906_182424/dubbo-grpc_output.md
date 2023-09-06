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
# Warmup Iteration   1: 1.896 ops/ms
# Warmup Iteration   2: 4.786 ops/ms
# Warmup Iteration   3: 6.067 ops/ms
Iteration   1: 6.309 ops/ms
Iteration   2: 6.440 ops/ms
Iteration   3: 6.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.397 ±(99.9%) 1.401 ops/ms [Average]
  (min, avg, max) = (6.309, 6.397, 6.444), stdev = 0.077
  CI (99.9%): [4.997, 7.798] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.074 ops/ms
# Warmup Iteration   2: 6.413 ops/ms
# Warmup Iteration   3: 6.713 ops/ms
Iteration   1: 6.940 ops/ms
Iteration   2: 7.041 ops/ms
Iteration   3: 7.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.060 ±(99.9%) 2.387 ops/ms [Average]
  (min, avg, max) = (6.940, 7.060, 7.199), stdev = 0.131
  CI (99.9%): [4.673, 9.446] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.277 ops/ms
# Warmup Iteration   2: 6.094 ops/ms
# Warmup Iteration   3: 6.369 ops/ms
Iteration   1: 6.300 ops/ms
Iteration   2: 6.533 ops/ms
Iteration   3: 6.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.470 ±(99.9%) 2.715 ops/ms [Average]
  (min, avg, max) = (6.300, 6.470, 6.577), stdev = 0.149
  CI (99.9%): [3.755, 9.185] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.054 ops/ms
# Warmup Iteration   2: 4.669 ops/ms
# Warmup Iteration   3: 5.162 ops/ms
Iteration   1: 5.041 ops/ms
Iteration   2: 5.180 ops/ms
Iteration   3: 5.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.094 ±(99.9%) 1.373 ops/ms [Average]
  (min, avg, max) = (5.041, 5.094, 5.180), stdev = 0.075
  CI (99.9%): [3.720, 6.467] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.604 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.306 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.207 ±(99.9%) 0.006 ms/op
Iteration   1: 5.007 ±(99.9%) 0.004 ms/op
Iteration   2: 5.086 ±(99.9%) 0.004 ms/op
Iteration   3: 5.085 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.059 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (5.007, 5.059, 5.086), stdev = 0.045
  CI (99.9%): [4.230, 5.889] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.740 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.018 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.629 ±(99.9%) 0.005 ms/op
Iteration   1: 4.616 ±(99.9%) 0.004 ms/op
Iteration   2: 4.664 ±(99.9%) 0.003 ms/op
Iteration   3: 4.574 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.618 ±(99.9%) 0.827 ms/op [Average]
  (min, avg, max) = (4.574, 4.618, 4.664), stdev = 0.045
  CI (99.9%): [3.791, 5.445] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.575 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.331 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.056 ±(99.9%) 0.014 ms/op
Iteration   1: 4.796 ±(99.9%) 0.005 ms/op
Iteration   2: 4.815 ±(99.9%) 0.006 ms/op
Iteration   3: 4.948 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.853 ±(99.9%) 1.510 ms/op [Average]
  (min, avg, max) = (4.796, 4.853, 4.948), stdev = 0.083
  CI (99.9%): [3.343, 6.363] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.411 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 6.865 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.317 ±(99.9%) 0.025 ms/op
Iteration   1: 6.373 ±(99.9%) 0.018 ms/op
Iteration   2: 6.223 ±(99.9%) 0.024 ms/op
Iteration   3: 6.197 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.264 ±(99.9%) 1.733 ms/op [Average]
  (min, avg, max) = (6.197, 6.264, 6.373), stdev = 0.095
  CI (99.9%): [4.532, 7.997] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.050 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 5.567 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.207 ±(99.9%) 0.019 ms/op
Iteration   1: 5.050 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   4.817 ms/op
                 createUser·p0.90:   6.487 ms/op
                 createUser·p0.95:   7.332 ms/op
                 createUser·p0.99:   10.371 ms/op
                 createUser·p0.999:  17.727 ms/op
                 createUser·p0.9999: 22.020 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   2: 5.107 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   4.858 ms/op
                 createUser·p0.90:   6.611 ms/op
                 createUser·p0.95:   7.447 ms/op
                 createUser·p0.99:   10.335 ms/op
                 createUser·p0.999:  14.029 ms/op
                 createUser·p0.9999: 24.957 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   3: 4.976 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.300 ms/op
                 createUser·p0.95:   6.947 ms/op
                 createUser·p0.99:   9.011 ms/op
                 createUser·p0.999:  16.645 ms/op
                 createUser·p0.9999: 23.695 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 190315
  mean =      5.044 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1841 
    [ 2.500,  5.000) = 106781 
    [ 5.000,  7.500) = 73950 
    [ 7.500, 10.000) = 5936 
    [10.000, 12.500) = 1154 
    [12.500, 15.000) = 410 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.463 ms/op
     p(95.0000) =      7.234 ms/op
     p(99.0000) =      9.912 ms/op
     p(99.9000) =     16.330 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     26.078 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.066 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.973 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.577 ±(99.9%) 0.014 ms/op
Iteration   1: 4.613 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   4.473 ms/op
                 existUser·p0.90:   5.956 ms/op
                 existUser·p0.95:   6.636 ms/op
                 existUser·p0.99:   8.471 ms/op
                 existUser·p0.999:  11.908 ms/op
                 existUser·p0.9999: 19.405 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   2: 4.578 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.352 ms/op
                 existUser·p0.50:   4.424 ms/op
                 existUser·p0.90:   5.759 ms/op
                 existUser·p0.95:   6.341 ms/op
                 existUser·p0.99:   8.913 ms/op
                 existUser·p0.999:  13.255 ms/op
                 existUser·p0.9999: 21.234 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   3: 4.568 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   4.383 ms/op
                 existUser·p0.90:   5.865 ms/op
                 existUser·p0.95:   6.636 ms/op
                 existUser·p0.99:   9.093 ms/op
                 existUser·p0.999:  16.268 ms/op
                 existUser·p0.9999: 21.037 ms/op
                 existUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 209443
  mean =      4.586 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5998 
    [ 2.500,  5.000) = 149390 
    [ 5.000,  7.500) = 49323 
    [ 7.500, 10.000) = 3744 
    [10.000, 12.500) = 704 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.865 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     13.364 ms/op
     p(99.9900) =     20.973 ms/op
     p(99.9990) =     21.621 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.927 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.368 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.025 ±(99.9%) 0.017 ms/op
Iteration   1: 4.868 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   4.694 ms/op
                 getUser·p0.90:   6.234 ms/op
                 getUser·p0.95:   6.881 ms/op
                 getUser·p0.99:   9.311 ms/op
                 getUser·p0.999:  13.167 ms/op
                 getUser·p0.9999: 19.478 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   2: 4.958 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   4.801 ms/op
                 getUser·p0.90:   6.185 ms/op
                 getUser·p0.95:   6.791 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  15.767 ms/op
                 getUser·p0.9999: 21.681 ms/op
                 getUser·p1.00:   22.151 ms/op

Iteration   3: 4.767 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   4.612 ms/op
                 getUser·p0.90:   6.029 ms/op
                 getUser·p0.95:   6.593 ms/op
                 getUser·p0.99:   8.700 ms/op
                 getUser·p0.999:  13.056 ms/op
                 getUser·p0.9999: 21.505 ms/op
                 getUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 197160
  mean =      4.863 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2631 
    [ 2.500,  5.000) = 121009 
    [ 5.000,  7.500) = 68510 
    [ 7.500, 10.000) = 3924 
    [10.000, 12.500) = 791 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      6.152 ms/op
     p(95.0000) =      6.758 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     22.163 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.909 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 6.590 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 6.153 ±(99.9%) 0.024 ms/op
Iteration   1: 6.177 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   5.825 ms/op
                 listUser·p0.90:   8.063 ms/op
                 listUser·p0.95:   9.257 ms/op
                 listUser·p0.99:   11.764 ms/op
                 listUser·p0.999:  18.194 ms/op
                 listUser·p0.9999: 31.330 ms/op
                 listUser·p1.00:   31.916 ms/op

Iteration   2: 6.138 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   8.061 ms/op
                 listUser·p0.95:   9.257 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  19.910 ms/op
                 listUser·p0.9999: 30.446 ms/op
                 listUser·p1.00:   30.900 ms/op

Iteration   3: 6.143 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   5.734 ms/op
                 listUser·p0.90:   8.315 ms/op
                 listUser·p0.95:   9.552 ms/op
                 listUser·p0.99:   12.616 ms/op
                 listUser·p0.999:  23.162 ms/op
                 listUser·p0.9999: 26.240 ms/op
                 listUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 155956
  mean =      6.153 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 30818 
    [ 5.000,  7.500) = 101765 
    [ 7.500, 10.000) = 17883 
    [10.000, 12.500) = 4070 
    [12.500, 15.000) = 915 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      5.784 ms/op
     p(90.0000) =      8.151 ms/op
     p(95.0000) =      9.355 ms/op
     p(99.0000) =     12.173 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     30.501 ms/op
     p(99.9990) =     31.824 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.397 ± 1.401  ops/ms
ClientGrpc.existUser                       thrpt       3   7.060 ± 2.387  ops/ms
ClientGrpc.getUser                         thrpt       3   6.470 ± 2.715  ops/ms
ClientGrpc.listUser                        thrpt       3   5.094 ± 1.373  ops/ms
ClientGrpc.createUser                       avgt       3   5.059 ± 0.829   ms/op
ClientGrpc.existUser                        avgt       3   4.618 ± 0.827   ms/op
ClientGrpc.getUser                          avgt       3   4.853 ± 1.510   ms/op
ClientGrpc.listUser                         avgt       3   6.264 ± 1.733   ms/op
ClientGrpc.createUser                     sample  190315   5.044 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.055           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.463           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.234           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.912           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.330           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.150           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.640           ms/op
ClientGrpc.existUser                      sample  209443   4.586 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.962           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.865           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.537           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.815           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.364           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.973           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.725           ms/op
ClientGrpc.getUser                        sample  197160   4.863 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.868           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.694           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.152           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.758           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.913           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.451           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.430           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.577           ms/op
ClientGrpc.listUser                       sample  155956   6.153 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.178           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.151           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.355           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.173           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.709           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.501           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.916           ms/op
