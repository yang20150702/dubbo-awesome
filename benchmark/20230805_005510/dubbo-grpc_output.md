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
# Warmup Iteration   1: 2.353 ops/ms
# Warmup Iteration   2: 6.009 ops/ms
# Warmup Iteration   3: 7.014 ops/ms
Iteration   1: 7.220 ops/ms
Iteration   2: 7.054 ops/ms
Iteration   3: 7.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.255 ±(99.9%) 4.012 ops/ms [Average]
  (min, avg, max) = (7.054, 7.255, 7.490), stdev = 0.220
  CI (99.9%): [3.243, 11.266] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.093 ops/ms
# Warmup Iteration   2: 7.220 ops/ms
# Warmup Iteration   3: 7.638 ops/ms
Iteration   1: 7.675 ops/ms
Iteration   2: 7.583 ops/ms
Iteration   3: 7.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.611 ±(99.9%) 1.018 ops/ms [Average]
  (min, avg, max) = (7.575, 7.611, 7.675), stdev = 0.056
  CI (99.9%): [6.594, 8.629] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.440 ops/ms
# Warmup Iteration   2: 6.883 ops/ms
# Warmup Iteration   3: 7.168 ops/ms
Iteration   1: 7.363 ops/ms
Iteration   2: 7.169 ops/ms
Iteration   3: 7.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.289 ±(99.9%) 1.902 ops/ms [Average]
  (min, avg, max) = (7.169, 7.289, 7.363), stdev = 0.104
  CI (99.9%): [5.386, 9.191] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.440 ops/ms
# Warmup Iteration   2: 4.744 ops/ms
# Warmup Iteration   3: 5.272 ops/ms
Iteration   1: 5.576 ops/ms
Iteration   2: 5.500 ops/ms
Iteration   3: 5.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.479 ±(99.9%) 1.987 ops/ms [Average]
  (min, avg, max) = (5.361, 5.479, 5.576), stdev = 0.109
  CI (99.9%): [3.492, 7.466] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.768 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.922 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.803 ±(99.9%) 0.008 ms/op
Iteration   1: 4.686 ±(99.9%) 0.005 ms/op
Iteration   2: 4.547 ±(99.9%) 0.004 ms/op
Iteration   3: 4.528 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.587 ±(99.9%) 1.577 ms/op [Average]
  (min, avg, max) = (4.528, 4.587, 4.686), stdev = 0.086
  CI (99.9%): [3.010, 6.164] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.392 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.377 ±(99.9%) 0.005 ms/op
Iteration   1: 4.220 ±(99.9%) 0.004 ms/op
Iteration   2: 4.186 ±(99.9%) 0.004 ms/op
Iteration   3: 4.287 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.231 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (4.186, 4.231, 4.287), stdev = 0.051
  CI (99.9%): [3.292, 5.170] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.473 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.744 ±(99.9%) 0.012 ms/op
Iteration   1: 4.665 ±(99.9%) 0.004 ms/op
Iteration   2: 4.605 ±(99.9%) 0.002 ms/op
Iteration   3: 4.569 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.613 ±(99.9%) 0.880 ms/op [Average]
  (min, avg, max) = (4.569, 4.613, 4.665), stdev = 0.048
  CI (99.9%): [3.732, 5.493] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.337 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 6.510 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.781 ±(99.9%) 0.013 ms/op
Iteration   1: 5.873 ±(99.9%) 0.012 ms/op
Iteration   2: 5.963 ±(99.9%) 0.017 ms/op
Iteration   3: 5.814 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.884 ±(99.9%) 1.368 ms/op [Average]
  (min, avg, max) = (5.814, 5.884, 5.963), stdev = 0.075
  CI (99.9%): [4.516, 7.251] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.727 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 4.838 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.404 ±(99.9%) 0.014 ms/op
Iteration   1: 4.566 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.751 ms/op
                 createUser·p0.95:   6.226 ms/op
                 createUser·p0.99:   7.559 ms/op
                 createUser·p0.999:  11.386 ms/op
                 createUser·p0.9999: 19.759 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   2: 4.370 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.546 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   7.941 ms/op
                 createUser·p0.999:  14.595 ms/op
                 createUser·p0.9999: 18.165 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   3: 4.558 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   4.440 ms/op
                 createUser·p0.90:   5.652 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  13.304 ms/op
                 createUser·p0.9999: 18.576 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 213513
  mean =      4.496 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2340 
    [ 2.500,  5.000) = 157141 
    [ 5.000,  7.500) = 51482 
    [ 7.500, 10.000) = 1857 
    [10.000, 12.500) = 365 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.661 ms/op
     p(95.0000) =      6.144 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     13.737 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     20.689 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 6.290 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.614 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.012 ms/op
Iteration   1: 4.228 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   4.096 ms/op
                 existUser·p0.90:   5.358 ms/op
                 existUser·p0.95:   5.890 ms/op
                 existUser·p0.99:   7.504 ms/op
                 existUser·p0.999:  12.472 ms/op
                 existUser·p0.9999: 18.804 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 4.181 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   4.096 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  11.895 ms/op
                 existUser·p0.9999: 18.745 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 4.130 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   4.026 ms/op
                 existUser·p0.90:   5.145 ms/op
                 existUser·p0.95:   5.620 ms/op
                 existUser·p0.99:   7.119 ms/op
                 existUser·p0.999:  10.062 ms/op
                 existUser·p0.9999: 21.725 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229633
  mean =      4.179 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5846 
    [ 2.500,  5.000) = 191850 
    [ 5.000,  7.500) = 30134 
    [ 7.500, 10.000) = 1415 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     20.679 ms/op
     p(99.9990) =     21.912 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 7.037 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.990 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.523 ±(99.9%) 0.014 ms/op
Iteration   1: 4.550 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   5.759 ms/op
                 getUser·p0.95:   6.259 ms/op
                 getUser·p0.99:   7.725 ms/op
                 getUser·p0.999:  11.677 ms/op
                 getUser·p0.9999: 18.641 ms/op
                 getUser·p1.00:   19.235 ms/op

Iteration   2: 4.677 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   4.563 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   6.341 ms/op
                 getUser·p0.99:   8.311 ms/op
                 getUser·p0.999:  12.440 ms/op
                 getUser·p0.9999: 16.184 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   3: 4.658 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.436 ms/op
                 getUser·p0.50:   4.489 ms/op
                 getUser·p0.90:   5.865 ms/op
                 getUser·p0.95:   6.463 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  13.418 ms/op
                 getUser·p0.9999: 19.497 ms/op
                 getUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 207281
  mean =      4.627 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2341 
    [ 2.500,  5.000) = 144234 
    [ 5.000,  7.500) = 57497 
    [ 7.500, 10.000) = 2562 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.841 ms/op
     p(95.0000) =      6.349 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     12.829 ms/op
     p(99.9900) =     19.113 ms/op
     p(99.9990) =     22.131 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 8.720 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 6.378 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.970 ±(99.9%) 0.022 ms/op
Iteration   1: 6.004 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   8.061 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   11.731 ms/op
                 listUser·p0.999:  18.014 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   2: 5.893 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   11.207 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 19.833 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   3: 5.964 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   7.856 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.583 ms/op
                 listUser·p0.999:  25.063 ms/op
                 listUser·p0.9999: 34.157 ms/op
                 listUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 161215
  mean =      5.953 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 129 
    [ 2.500,  5.000) = 40726 
    [ 5.000,  7.500) = 99955 
    [ 7.500, 10.000) = 16444 
    [10.000, 12.500) = 2984 
    [12.500, 15.000) = 618 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      5.636 ms/op
     p(90.0000) =      7.881 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     11.469 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     30.474 ms/op
     p(99.9990) =     35.284 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.255 ± 4.012  ops/ms
ClientGrpc.existUser                       thrpt       3   7.611 ± 1.018  ops/ms
ClientGrpc.getUser                         thrpt       3   7.289 ± 1.902  ops/ms
ClientGrpc.listUser                        thrpt       3   5.479 ± 1.987  ops/ms
ClientGrpc.createUser                       avgt       3   4.587 ± 1.577   ms/op
ClientGrpc.existUser                        avgt       3   4.231 ± 0.939   ms/op
ClientGrpc.getUser                          avgt       3   4.613 ± 0.880   ms/op
ClientGrpc.listUser                         avgt       3   5.884 ± 1.368   ms/op
ClientGrpc.createUser                     sample  213513   4.496 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.102           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.661           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.144           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.807           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.737           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.169           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.758           ms/op
ClientGrpc.existUser                      sample  229633   4.179 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.701           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.235           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.726           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.152           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.354           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.679           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.020           ms/op
ClientGrpc.getUser                        sample  207281   4.627 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.188           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.841           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.349           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.118           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.829           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.113           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.348           ms/op
ClientGrpc.listUser                       sample  161215   5.953 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.337           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.881           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.946           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.469           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.907           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.474           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.324           ms/op
