# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.096 ops/ms
# Warmup Iteration   2: 6.985 ops/ms
# Warmup Iteration   3: 8.229 ops/ms
Iteration   1: 8.159 ops/ms
Iteration   2: 8.191 ops/ms
Iteration   3: 8.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.136 ±(99.9%) 1.289 ops/ms [Average]
  (min, avg, max) = (8.056, 8.136, 8.191), stdev = 0.071
  CI (99.9%): [6.847, 9.424] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.808 ops/ms
# Warmup Iteration   2: 8.567 ops/ms
# Warmup Iteration   3: 8.777 ops/ms
Iteration   1: 8.932 ops/ms
Iteration   2: 9.214 ops/ms
Iteration   3: 8.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.995 ±(99.9%) 3.568 ops/ms [Average]
  (min, avg, max) = (8.838, 8.995, 9.214), stdev = 0.196
  CI (99.9%): [5.427, 12.562] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.953 ops/ms
# Warmup Iteration   2: 7.797 ops/ms
# Warmup Iteration   3: 8.176 ops/ms
Iteration   1: 8.194 ops/ms
Iteration   2: 8.019 ops/ms
Iteration   3: 8.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.261 ±(99.9%) 5.134 ops/ms [Average]
  (min, avg, max) = (8.019, 8.261, 8.570), stdev = 0.281
  CI (99.9%): [3.126, 13.395] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.439 ops/ms
# Warmup Iteration   2: 5.721 ops/ms
# Warmup Iteration   3: 6.352 ops/ms
Iteration   1: 6.478 ops/ms
Iteration   2: 6.289 ops/ms
Iteration   3: 6.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.380 ±(99.9%) 1.723 ops/ms [Average]
  (min, avg, max) = (6.289, 6.380, 6.478), stdev = 0.094
  CI (99.9%): [4.658, 8.103] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.774 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.006 ms/op
Iteration   1: 3.930 ±(99.9%) 0.004 ms/op
Iteration   2: 4.043 ±(99.9%) 0.004 ms/op
Iteration   3: 4.030 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.001 ±(99.9%) 1.134 ms/op [Average]
  (min, avg, max) = (3.930, 4.001, 4.043), stdev = 0.062
  CI (99.9%): [2.867, 5.135] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.960 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.934 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.003 ms/op
Iteration   1: 3.712 ±(99.9%) 0.003 ms/op
Iteration   2: 3.731 ±(99.9%) 0.003 ms/op
Iteration   3: 3.796 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.746 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.712, 3.746, 3.796), stdev = 0.044
  CI (99.9%): [2.948, 4.544] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.375 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.004 ms/op
Iteration   1: 3.680 ±(99.9%) 0.003 ms/op
Iteration   2: 3.599 ±(99.9%) 0.006 ms/op
Iteration   3: 3.699 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.659 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (3.599, 3.659, 3.699), stdev = 0.053
  CI (99.9%): [2.693, 4.625] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.727 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.879 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.884 ±(99.9%) 0.007 ms/op
Iteration   1: 5.015 ±(99.9%) 0.008 ms/op
Iteration   2: 4.819 ±(99.9%) 0.005 ms/op
Iteration   3: 4.852 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.895 ±(99.9%) 1.914 ms/op [Average]
  (min, avg, max) = (4.819, 4.895, 5.015), stdev = 0.105
  CI (99.9%): [2.981, 6.809] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.358 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.009 ms/op
Iteration   1: 3.761 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  7.709 ms/op
                 createUser·p0.9999: 15.294 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   2: 3.675 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  9.828 ms/op
                 createUser·p0.9999: 16.358 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   3: 3.588 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  14.779 ms/op
                 createUser·p0.9999: 27.101 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261463
  mean =      3.673 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7896 
    [ 2.500,  5.000) = 245380 
    [ 5.000,  7.500) = 7518 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =      9.930 ms/op
     p(99.9900) =     26.865 ms/op
     p(99.9990) =     27.439 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.742 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.010 ms/op
Iteration   1: 3.476 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  8.352 ms/op
                 existUser·p0.9999: 16.561 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   2: 3.639 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  10.304 ms/op
                 existUser·p0.9999: 15.060 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   3: 3.491 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  7.436 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271820
  mean =      3.534 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12809 
    [ 2.500,  5.000) = 252745 
    [ 5.000,  7.500) = 5744 
    [ 7.500, 10.000) = 325 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     20.048 ms/op
     p(99.9990) =     20.793 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.393 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.010 ms/op
Iteration   1: 3.809 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  13.712 ms/op
                 getUser·p0.9999: 17.275 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   2: 3.728 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   5.831 ms/op
                 getUser·p0.999:  8.390 ms/op
                 getUser·p0.9999: 17.479 ms/op
                 getUser·p1.00:   18.973 ms/op

Iteration   3: 3.832 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  9.799 ms/op
                 getUser·p0.9999: 19.921 ms/op
                 getUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253584
  mean =      3.789 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7328 
    [ 2.500,  5.000) = 233497 
    [ 5.000,  7.500) = 12026 
    [ 7.500, 10.000) = 479 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     10.024 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     21.314 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.555 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.333 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.813 ±(99.9%) 0.016 ms/op
Iteration   1: 4.863 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  19.595 ms/op
                 listUser·p0.9999: 22.094 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   2: 5.078 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   6.668 ms/op
                 listUser·p0.95:   7.520 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  20.416 ms/op
                 listUser·p0.9999: 23.049 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 5.085 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   6.619 ms/op
                 listUser·p0.95:   7.537 ms/op
                 listUser·p0.99:   9.487 ms/op
                 listUser·p0.999:  20.683 ms/op
                 listUser·p0.9999: 23.934 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 191633
  mean =      5.006 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 362 
    [ 2.500,  5.000) = 122484 
    [ 5.000,  7.500) = 60225 
    [ 7.500, 10.000) = 7469 
    [10.000, 12.500) = 613 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 167 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.463 ms/op
     p(95.0000) =      7.356 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     20.099 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     24.743 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.136 ± 1.289  ops/ms
ClientGrpc.existUser                       thrpt       3   8.995 ± 3.568  ops/ms
ClientGrpc.getUser                         thrpt       3   8.261 ± 5.134  ops/ms
ClientGrpc.listUser                        thrpt       3   6.380 ± 1.723  ops/ms
ClientGrpc.createUser                       avgt       3   4.001 ± 1.134   ms/op
ClientGrpc.existUser                        avgt       3   3.746 ± 0.798   ms/op
ClientGrpc.getUser                          avgt       3   3.659 ± 0.966   ms/op
ClientGrpc.listUser                         avgt       3   4.895 ± 1.914   ms/op
ClientGrpc.createUser                     sample  261463   3.673 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.630           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.767           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.930           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.865           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.525           ms/op
ClientGrpc.existUser                      sample  271820   3.534 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.758           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.661           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.579           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.487           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.048           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.906           ms/op
ClientGrpc.getUser                        sample  253584   3.789 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.782           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.029           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.024           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.399           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.365           ms/op
ClientGrpc.listUser                       sample  191633   5.006 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.114           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.463           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.356           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.257           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.099           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.872           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.773           ms/op
