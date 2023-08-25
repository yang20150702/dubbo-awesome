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
# Warmup Iteration   1: 1.854 ops/ms
# Warmup Iteration   2: 4.830 ops/ms
# Warmup Iteration   3: 6.439 ops/ms
Iteration   1: 6.829 ops/ms
Iteration   2: 6.803 ops/ms
Iteration   3: 6.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.833 ±(99.9%) 0.572 ops/ms [Average]
  (min, avg, max) = (6.803, 6.833, 6.866), stdev = 0.031
  CI (99.9%): [6.260, 7.405] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.750 ops/ms
# Warmup Iteration   2: 6.035 ops/ms
# Warmup Iteration   3: 6.680 ops/ms
Iteration   1: 7.286 ops/ms
Iteration   2: 7.410 ops/ms
Iteration   3: 7.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.381 ±(99.9%) 1.543 ops/ms [Average]
  (min, avg, max) = (7.286, 7.381, 7.447), stdev = 0.085
  CI (99.9%): [5.838, 8.924] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ops/ms
# Warmup Iteration   2: 6.330 ops/ms
# Warmup Iteration   3: 6.250 ops/ms
Iteration   1: 6.614 ops/ms
Iteration   2: 6.691 ops/ms
Iteration   3: 6.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.678 ±(99.9%) 1.073 ops/ms [Average]
  (min, avg, max) = (6.614, 6.678, 6.729), stdev = 0.059
  CI (99.9%): [5.605, 7.751] (assumes normal distribution)


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
# Warmup Iteration   1: 3.322 ops/ms
# Warmup Iteration   2: 4.655 ops/ms
# Warmup Iteration   3: 5.085 ops/ms
Iteration   1: 5.170 ops/ms
Iteration   2: 5.072 ops/ms
Iteration   3: 5.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.120 ±(99.9%) 0.901 ops/ms [Average]
  (min, avg, max) = (5.072, 5.120, 5.170), stdev = 0.049
  CI (99.9%): [4.219, 6.021] (assumes normal distribution)


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
# Warmup Iteration   1: 8.463 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.658 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.069 ±(99.9%) 0.015 ms/op
Iteration   1: 4.740 ±(99.9%) 0.004 ms/op
Iteration   2: 4.568 ±(99.9%) 0.004 ms/op
Iteration   3: 4.653 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.654 ±(99.9%) 1.573 ms/op [Average]
  (min, avg, max) = (4.568, 4.654, 4.740), stdev = 0.086
  CI (99.9%): [3.080, 6.227] (assumes normal distribution)


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
# Warmup Iteration   1: 6.589 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.882 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.632 ±(99.9%) 0.005 ms/op
Iteration   1: 4.461 ±(99.9%) 0.004 ms/op
Iteration   2: 4.430 ±(99.9%) 0.005 ms/op
Iteration   3: 4.485 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.459 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (4.430, 4.459, 4.485), stdev = 0.027
  CI (99.9%): [3.961, 4.957] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.836 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.024 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.935 ±(99.9%) 0.026 ms/op
Iteration   1: 4.680 ±(99.9%) 0.003 ms/op
Iteration   2: 4.689 ±(99.9%) 0.003 ms/op
Iteration   3: 4.599 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.656 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (4.599, 4.656, 4.689), stdev = 0.050
  CI (99.9%): [3.747, 5.565] (assumes normal distribution)


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
# Warmup Iteration   1: 9.550 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.401 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 6.050 ±(99.9%) 0.020 ms/op
Iteration   1: 6.086 ±(99.9%) 0.018 ms/op
Iteration   2: 5.655 ±(99.9%) 0.013 ms/op
Iteration   3: 5.739 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.827 ±(99.9%) 4.172 ms/op [Average]
  (min, avg, max) = (5.655, 5.827, 6.086), stdev = 0.229
  CI (99.9%): [1.654, 9.999] (assumes normal distribution)


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
# Warmup Iteration   1: 7.348 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 4.861 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.742 ±(99.9%) 0.018 ms/op
Iteration   1: 4.830 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   6.234 ms/op
                 createUser·p0.95:   6.980 ms/op
                 createUser·p0.99:   9.388 ms/op
                 createUser·p0.999:  15.589 ms/op
                 createUser·p0.9999: 17.052 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   2: 4.736 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   4.571 ms/op
                 createUser·p0.90:   6.193 ms/op
                 createUser·p0.95:   6.840 ms/op
                 createUser·p0.99:   9.421 ms/op
                 createUser·p0.999:  16.903 ms/op
                 createUser·p0.9999: 20.357 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   3: 4.738 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   4.530 ms/op
                 createUser·p0.90:   5.947 ms/op
                 createUser·p0.95:   6.627 ms/op
                 createUser·p0.99:   9.290 ms/op
                 createUser·p0.999:  14.609 ms/op
                 createUser·p0.9999: 22.159 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 201298
  mean =      4.768 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4097 
    [ 2.500,  5.000) = 130826 
    [ 5.000,  7.500) = 60287 
    [ 7.500, 10.000) = 4692 
    [10.000, 12.500) = 927 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      6.832 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     16.215 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     23.321 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 6.784 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.859 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.652 ±(99.9%) 0.017 ms/op
Iteration   1: 4.652 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.432 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   5.956 ms/op
                 existUser·p0.95:   6.685 ms/op
                 existUser·p0.99:   9.332 ms/op
                 existUser·p0.999:  15.434 ms/op
                 existUser·p0.9999: 18.625 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   2: 4.542 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.677 ms/op
                 existUser·p0.95:   6.242 ms/op
                 existUser·p0.99:   8.602 ms/op
                 existUser·p0.999:  14.470 ms/op
                 existUser·p0.9999: 19.005 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   3: 4.285 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   5.964 ms/op
                 existUser·p0.99:   8.372 ms/op
                 existUser·p0.999:  15.128 ms/op
                 existUser·p0.9999: 21.692 ms/op
                 existUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 213818
  mean =      4.488 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4679 
    [ 2.500,  5.000) = 161120 
    [ 5.000,  7.500) = 43560 
    [ 7.500, 10.000) = 3334 
    [10.000, 12.500) = 532 
    [12.500, 15.000) = 361 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.308 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     22.016 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 7.773 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.238 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.929 ±(99.9%) 0.018 ms/op
Iteration   1: 4.844 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   4.604 ms/op
                 getUser·p0.90:   6.136 ms/op
                 getUser·p0.95:   6.939 ms/op
                 getUser·p0.99:   10.093 ms/op
                 getUser·p0.999:  17.138 ms/op
                 getUser·p0.9999: 21.181 ms/op
                 getUser·p1.00:   21.692 ms/op

Iteration   2: 4.861 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   4.661 ms/op
                 getUser·p0.90:   6.218 ms/op
                 getUser·p0.95:   6.930 ms/op
                 getUser·p0.99:   9.519 ms/op
                 getUser·p0.999:  13.120 ms/op
                 getUser·p0.9999: 19.243 ms/op
                 getUser·p1.00:   20.283 ms/op

Iteration   3: 5.048 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   4.809 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   7.381 ms/op
                 getUser·p0.99:   10.748 ms/op
                 getUser·p0.999:  15.374 ms/op
                 getUser·p0.9999: 25.198 ms/op
                 getUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 195217
  mean =      4.916 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2750 
    [ 2.500,  5.000) = 119150 
    [ 5.000,  7.500) = 65841 
    [ 7.500, 10.000) = 5356 
    [10.000, 12.500) = 1507 
    [12.500, 15.000) = 388 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      6.283 ms/op
     p(95.0000) =      7.086 ms/op
     p(99.0000) =     10.155 ms/op
     p(99.9000) =     15.583 ms/op
     p(99.9900) =     23.985 ms/op
     p(99.9990) =     25.395 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 9.166 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 7.022 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.978 ±(99.9%) 0.027 ms/op
Iteration   1: 5.877 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.827 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   7.881 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.749 ms/op
                 listUser·p0.999:  16.082 ms/op
                 listUser·p0.9999: 25.664 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   2: 5.970 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   7.913 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   11.633 ms/op
                 listUser·p0.999:  22.217 ms/op
                 listUser·p0.9999: 25.175 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   3: 5.991 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   8.036 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   11.567 ms/op
                 listUser·p0.999:  21.495 ms/op
                 listUser·p0.9999: 26.269 ms/op
                 listUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 161442
  mean =      5.946 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 42892 
    [ 5.000,  7.500) = 96695 
    [ 7.500, 10.000) = 17674 
    [10.000, 12.500) = 3075 
    [12.500, 15.000) = 651 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      5.587 ms/op
     p(90.0000) =      7.946 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     11.649 ms/op
     p(99.9000) =     20.859 ms/op
     p(99.9900) =     25.807 ms/op
     p(99.9990) =     27.854 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.833 ± 0.572  ops/ms
ClientGrpc.existUser                       thrpt       3   7.381 ± 1.543  ops/ms
ClientGrpc.getUser                         thrpt       3   6.678 ± 1.073  ops/ms
ClientGrpc.listUser                        thrpt       3   5.120 ± 0.901  ops/ms
ClientGrpc.createUser                       avgt       3   4.654 ± 1.573   ms/op
ClientGrpc.existUser                        avgt       3   4.459 ± 0.498   ms/op
ClientGrpc.getUser                          avgt       3   4.656 ± 0.909   ms/op
ClientGrpc.listUser                         avgt       3   5.827 ± 4.172   ms/op
ClientGrpc.createUser                     sample  201298   4.768 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.900           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.128           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.832           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.372           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.215           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.823           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.396           ms/op
ClientGrpc.existUser                      sample  213818   4.488 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.432           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.685           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.308           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.798           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.139           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.463           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.184           ms/op
ClientGrpc.getUser                        sample  195217   4.916 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.085           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.283           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.086           ms/op
ClientGrpc.getUser:getUser·p0.99          sample          10.155           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.583           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.985           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.395           ms/op
ClientGrpc.listUser                       sample  161442   5.946 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.470           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.946           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.946           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.649           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.859           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.807           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.901           ms/op
