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
# Warmup Iteration   1: 3.322 ops/ms
# Warmup Iteration   2: 6.669 ops/ms
# Warmup Iteration   3: 8.186 ops/ms
Iteration   1: 8.745 ops/ms
Iteration   2: 8.883 ops/ms
Iteration   3: 8.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.809 ±(99.9%) 1.274 ops/ms [Average]
  (min, avg, max) = (8.745, 8.809, 8.883), stdev = 0.070
  CI (99.9%): [7.536, 10.083] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.990 ops/ms
# Warmup Iteration   2: 8.643 ops/ms
# Warmup Iteration   3: 9.292 ops/ms
Iteration   1: 9.293 ops/ms
Iteration   2: 9.601 ops/ms
Iteration   3: 9.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.362 ±(99.9%) 3.884 ops/ms [Average]
  (min, avg, max) = (9.193, 9.362, 9.601), stdev = 0.213
  CI (99.9%): [5.478, 13.246] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.377 ops/ms
# Warmup Iteration   2: 8.157 ops/ms
# Warmup Iteration   3: 8.604 ops/ms
Iteration   1: 8.778 ops/ms
Iteration   2: 8.855 ops/ms
Iteration   3: 8.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.838 ±(99.9%) 0.975 ops/ms [Average]
  (min, avg, max) = (8.778, 8.838, 8.880), stdev = 0.053
  CI (99.9%): [7.863, 9.813] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ops/ms
# Warmup Iteration   2: 6.443 ops/ms
# Warmup Iteration   3: 6.779 ops/ms
Iteration   1: 6.869 ops/ms
Iteration   2: 6.782 ops/ms
Iteration   3: 6.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.788 ±(99.9%) 1.440 ops/ms [Average]
  (min, avg, max) = (6.712, 6.788, 6.869), stdev = 0.079
  CI (99.9%): [5.348, 8.228] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.253 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.007 ms/op
Iteration   1: 3.602 ±(99.9%) 0.003 ms/op
Iteration   2: 3.565 ±(99.9%) 0.003 ms/op
Iteration   3: 3.565 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.577 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (3.565, 3.577, 3.602), stdev = 0.021
  CI (99.9%): [3.194, 3.961] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.771 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.002 ms/op
Iteration   1: 3.422 ±(99.9%) 0.004 ms/op
Iteration   2: 3.444 ±(99.9%) 0.003 ms/op
Iteration   3: 3.469 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.445 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (3.422, 3.445, 3.469), stdev = 0.024
  CI (99.9%): [3.010, 3.880] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.318 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.654 ±(99.9%) 0.007 ms/op
Iteration   1: 3.585 ±(99.9%) 0.005 ms/op
Iteration   2: 3.595 ±(99.9%) 0.007 ms/op
Iteration   3: 3.635 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.605 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (3.585, 3.605, 3.635), stdev = 0.026
  CI (99.9%): [3.122, 4.087] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.095 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.958 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.785 ±(99.9%) 0.017 ms/op
Iteration   1: 4.702 ±(99.9%) 0.017 ms/op
Iteration   2: 4.700 ±(99.9%) 0.010 ms/op
Iteration   3: 4.693 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.698 ±(99.9%) 0.088 ms/op [Average]
  (min, avg, max) = (4.693, 4.698, 4.702), stdev = 0.005
  CI (99.9%): [4.610, 4.786] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.456 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.008 ms/op
Iteration   1: 3.532 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  11.877 ms/op
                 createUser·p0.9999: 20.019 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   2: 3.551 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.165 ms/op
                 createUser·p0.999:  10.846 ms/op
                 createUser·p0.9999: 21.955 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   3: 3.539 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  8.432 ms/op
                 createUser·p0.9999: 35.717 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 271044
  mean =      3.541 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9438 
    [ 2.500,  5.000) = 258189 
    [ 5.000,  7.500) = 2807 
    [ 7.500, 10.000) = 318 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     10.600 ms/op
     p(99.9900) =     32.470 ms/op
     p(99.9990) =     35.783 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.254 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.007 ms/op
Iteration   1: 3.420 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  8.109 ms/op
                 existUser·p0.9999: 14.740 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   2: 3.437 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.796 ms/op
                 existUser·p0.9999: 16.063 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   3: 3.494 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  7.963 ms/op
                 existUser·p0.9999: 30.993 ms/op
                 existUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 278333
  mean =      3.450 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9799 
    [ 2.500,  5.000) = 264543 
    [ 5.000,  7.500) = 3527 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =      8.400 ms/op
     p(99.9900) =     30.409 ms/op
     p(99.9990) =     31.242 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.778 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.008 ms/op
Iteration   1: 3.639 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  9.973 ms/op
                 getUser·p0.9999: 17.136 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   2: 3.666 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  9.306 ms/op
                 getUser·p0.9999: 15.963 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   3: 3.693 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  11.615 ms/op
                 getUser·p0.9999: 21.135 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261949
  mean =      3.666 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7581 
    [ 2.500,  5.000) = 246459 
    [ 5.000,  7.500) = 6952 
    [ 7.500, 10.000) = 687 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     10.045 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     21.455 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.253 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.158 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.782 ±(99.9%) 0.014 ms/op
Iteration   1: 4.750 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  14.937 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   2: 4.839 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.989 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   7.053 ms/op
                 listUser·p0.99:   8.900 ms/op
                 listUser·p0.999:  21.815 ms/op
                 listUser·p0.9999: 28.644 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   3: 4.579 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.751 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 26.215 ms/op
                 listUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203390
  mean =      4.720 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 282 
    [ 2.500,  5.000) = 155474 
    [ 5.000,  7.500) = 42334 
    [ 7.500, 10.000) = 4460 
    [10.000, 12.500) = 488 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.939 ms/op
     p(95.0000) =      6.726 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     27.241 ms/op
     p(99.9990) =     30.915 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.809 ± 1.274  ops/ms
ClientGrpc.existUser                       thrpt       3   9.362 ± 3.884  ops/ms
ClientGrpc.getUser                         thrpt       3   8.838 ± 0.975  ops/ms
ClientGrpc.listUser                        thrpt       3   6.788 ± 1.440  ops/ms
ClientGrpc.createUser                       avgt       3   3.577 ± 0.384   ms/op
ClientGrpc.existUser                        avgt       3   3.445 ± 0.435   ms/op
ClientGrpc.getUser                          avgt       3   3.605 ± 0.482   ms/op
ClientGrpc.listUser                         avgt       3   4.698 ± 0.088   ms/op
ClientGrpc.createUser                     sample  271044   3.541 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.724           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.080           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.235           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.600           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.470           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.783           ms/op
ClientGrpc.existUser                      sample  278333   3.450 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.923           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.400           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.409           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.621           ms/op
ClientGrpc.getUser                        sample  261949   3.666 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.907           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.972           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.045           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.644           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.364           ms/op
ClientGrpc.listUser                       sample  203390   4.720 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.989           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.602           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.564           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.241           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.064           ms/op
