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
# Warmup Iteration   1: 3.235 ops/ms
# Warmup Iteration   2: 6.958 ops/ms
# Warmup Iteration   3: 8.070 ops/ms
Iteration   1: 8.157 ops/ms
Iteration   2: 8.527 ops/ms
Iteration   3: 8.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.398 ±(99.9%) 3.811 ops/ms [Average]
  (min, avg, max) = (8.157, 8.398, 8.527), stdev = 0.209
  CI (99.9%): [4.588, 12.209] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.681 ops/ms
# Warmup Iteration   2: 8.445 ops/ms
# Warmup Iteration   3: 8.604 ops/ms
Iteration   1: 8.934 ops/ms
Iteration   2: 8.811 ops/ms
Iteration   3: 8.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.901 ±(99.9%) 1.442 ops/ms [Average]
  (min, avg, max) = (8.811, 8.901, 8.959), stdev = 0.079
  CI (99.9%): [7.459, 10.343] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.344 ops/ms
# Warmup Iteration   2: 7.714 ops/ms
# Warmup Iteration   3: 8.638 ops/ms
Iteration   1: 8.675 ops/ms
Iteration   2: 8.722 ops/ms
Iteration   3: 8.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.702 ±(99.9%) 0.434 ops/ms [Average]
  (min, avg, max) = (8.675, 8.702, 8.722), stdev = 0.024
  CI (99.9%): [8.268, 9.135] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.666 ops/ms
# Warmup Iteration   2: 6.027 ops/ms
# Warmup Iteration   3: 6.593 ops/ms
Iteration   1: 6.648 ops/ms
Iteration   2: 6.663 ops/ms
Iteration   3: 6.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.613 ±(99.9%) 1.344 ops/ms [Average]
  (min, avg, max) = (6.529, 6.613, 6.663), stdev = 0.074
  CI (99.9%): [5.269, 7.958] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.090 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.004 ms/op
Iteration   1: 3.749 ±(99.9%) 0.006 ms/op
Iteration   2: 3.631 ±(99.9%) 0.007 ms/op
Iteration   3: 3.640 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.673 ±(99.9%) 1.192 ms/op [Average]
  (min, avg, max) = (3.631, 3.673, 3.749), stdev = 0.065
  CI (99.9%): [2.482, 4.865] (assumes normal distribution)


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
# Warmup Iteration   1: 4.743 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.003 ms/op
Iteration   1: 3.492 ±(99.9%) 0.002 ms/op
Iteration   2: 3.475 ±(99.9%) 0.004 ms/op
Iteration   3: 3.471 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.479 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (3.471, 3.479, 3.492), stdev = 0.012
  CI (99.9%): [3.268, 3.691] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.397 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.002 ms/op
Iteration   1: 3.708 ±(99.9%) 0.004 ms/op
Iteration   2: 3.680 ±(99.9%) 0.004 ms/op
Iteration   3: 3.690 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.693 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (3.680, 3.693, 3.708), stdev = 0.014
  CI (99.9%): [3.435, 3.950] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.662 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.879 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.823 ±(99.9%) 0.013 ms/op
Iteration   1: 4.836 ±(99.9%) 0.021 ms/op
Iteration   2: 4.664 ±(99.9%) 0.014 ms/op
Iteration   3: 4.696 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.732 ±(99.9%) 1.668 ms/op [Average]
  (min, avg, max) = (4.664, 4.732, 4.836), stdev = 0.091
  CI (99.9%): [3.064, 6.400] (assumes normal distribution)


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
# Warmup Iteration   1: 5.407 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.696 ±(99.9%) 0.009 ms/op
Iteration   1: 3.617 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.559 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  11.239 ms/op
                 createUser·p0.9999: 19.240 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   2: 3.661 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  12.380 ms/op
                 createUser·p0.9999: 24.918 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   3: 3.653 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  9.814 ms/op
                 createUser·p0.9999: 24.584 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263388
  mean =      3.644 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9344 
    [ 2.500,  5.000) = 245497 
    [ 5.000,  7.500) = 7528 
    [ 7.500, 10.000) = 652 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     11.092 ms/op
     p(99.9900) =     24.292 ms/op
     p(99.9990) =     25.854 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 4.982 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.009 ms/op
Iteration   1: 3.418 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  9.912 ms/op
                 existUser·p0.9999: 22.357 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   2: 3.459 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.999 ms/op
                 existUser·p0.999:  10.077 ms/op
                 existUser·p0.9999: 18.434 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   3: 3.406 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.452 ms/op
                 existUser·p0.999:  9.456 ms/op
                 existUser·p0.9999: 35.193 ms/op
                 existUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279971
  mean =      3.428 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9820 
    [ 2.500,  5.000) = 264978 
    [ 5.000,  7.500) = 4475 
    [ 7.500, 10.000) = 450 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.830 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     35.258 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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
# Warmup Iteration   1: 5.163 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.009 ms/op
Iteration   1: 3.653 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.838 ms/op
                 getUser·p0.999:  8.526 ms/op
                 getUser·p0.9999: 23.642 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   2: 3.653 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  9.008 ms/op
                 getUser·p0.9999: 16.785 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   3: 3.649 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  14.052 ms/op
                 getUser·p0.9999: 27.573 ms/op
                 getUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262903
  mean =      3.652 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7168 
    [ 2.500,  5.000) = 246733 
    [ 5.000,  7.500) = 7907 
    [ 7.500, 10.000) = 789 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     11.013 ms/op
     p(99.9900) =     25.793 ms/op
     p(99.9990) =     27.844 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 6.100 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.130 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.879 ±(99.9%) 0.016 ms/op
Iteration   1: 4.812 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  16.247 ms/op
                 listUser·p0.9999: 33.732 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   2: 4.781 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  18.094 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   3: 4.745 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.822 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  20.185 ms/op
                 listUser·p0.9999: 25.494 ms/op
                 listUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200652
  mean =      4.779 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 428 
    [ 2.500,  5.000) = 150930 
    [ 5.000,  7.500) = 43905 
    [ 7.500, 10.000) = 4622 
    [10.000, 12.500) = 364 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.827 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     18.034 ms/op
     p(99.9900) =     29.028 ms/op
     p(99.9990) =     35.122 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.398 ± 3.811  ops/ms
ClientGrpc.existUser                       thrpt       3   8.901 ± 1.442  ops/ms
ClientGrpc.getUser                         thrpt       3   8.702 ± 0.434  ops/ms
ClientGrpc.listUser                        thrpt       3   6.613 ± 1.344  ops/ms
ClientGrpc.createUser                       avgt       3   3.673 ± 1.192   ms/op
ClientGrpc.existUser                        avgt       3   3.479 ± 0.211   ms/op
ClientGrpc.getUser                          avgt       3   3.693 ± 0.258   ms/op
ClientGrpc.listUser                         avgt       3   4.732 ± 1.668   ms/op
ClientGrpc.createUser                     sample  263388   3.644 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.665           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.038           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.092           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.292           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.854           ms/op
ClientGrpc.existUser                      sample  279971   3.428 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.673           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.924           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.612           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.830           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          34.669           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.324           ms/op
ClientGrpc.getUser                        sample  262903   3.652 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.994           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.013           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.013           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.793           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.951           ms/op
ClientGrpc.listUser                       sample  200652   4.779 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.157           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.827           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.536           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.034           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.028           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.127           ms/op
