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
# Warmup Iteration   1: 2.083 ops/ms
# Warmup Iteration   2: 4.551 ops/ms
# Warmup Iteration   3: 6.460 ops/ms
Iteration   1: 6.731 ops/ms
Iteration   2: 6.844 ops/ms
Iteration   3: 6.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.800 ±(99.9%) 1.109 ops/ms [Average]
  (min, avg, max) = (6.731, 6.800, 6.844), stdev = 0.061
  CI (99.9%): [5.691, 7.909] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.903 ops/ms
# Warmup Iteration   2: 6.885 ops/ms
# Warmup Iteration   3: 7.362 ops/ms
Iteration   1: 7.263 ops/ms
Iteration   2: 7.520 ops/ms
Iteration   3: 7.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.365 ±(99.9%) 2.485 ops/ms [Average]
  (min, avg, max) = (7.263, 7.365, 7.520), stdev = 0.136
  CI (99.9%): [4.880, 9.850] (assumes normal distribution)


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
# Warmup Iteration   1: 3.895 ops/ms
# Warmup Iteration   2: 6.455 ops/ms
# Warmup Iteration   3: 6.864 ops/ms
Iteration   1: 7.000 ops/ms
Iteration   2: 7.025 ops/ms
Iteration   3: 6.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.001 ±(99.9%) 0.433 ops/ms [Average]
  (min, avg, max) = (6.978, 7.001, 7.025), stdev = 0.024
  CI (99.9%): [6.568, 7.433] (assumes normal distribution)


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
# Warmup Iteration   1: 3.651 ops/ms
# Warmup Iteration   2: 4.716 ops/ms
# Warmup Iteration   3: 5.385 ops/ms
Iteration   1: 5.458 ops/ms
Iteration   2: 5.382 ops/ms
Iteration   3: 5.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.450 ±(99.9%) 1.161 ops/ms [Average]
  (min, avg, max) = (5.382, 5.450, 5.508), stdev = 0.064
  CI (99.9%): [4.289, 6.610] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.161 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.183 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.779 ±(99.9%) 0.013 ms/op
Iteration   1: 4.830 ±(99.9%) 0.006 ms/op
Iteration   2: 4.659 ±(99.9%) 0.003 ms/op
Iteration   3: 4.681 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.723 ±(99.9%) 1.700 ms/op [Average]
  (min, avg, max) = (4.659, 4.723, 4.830), stdev = 0.093
  CI (99.9%): [3.024, 6.423] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.786 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.683 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.004 ms/op
Iteration   1: 4.340 ±(99.9%) 0.003 ms/op
Iteration   2: 4.385 ±(99.9%) 0.003 ms/op
Iteration   3: 4.149 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.291 ±(99.9%) 2.287 ms/op [Average]
  (min, avg, max) = (4.149, 4.291, 4.385), stdev = 0.125
  CI (99.9%): [2.004, 6.578] (assumes normal distribution)


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
# Warmup Iteration   1: 6.904 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.783 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.713 ±(99.9%) 0.003 ms/op
Iteration   1: 4.365 ±(99.9%) 0.003 ms/op
Iteration   2: 4.392 ±(99.9%) 0.004 ms/op
Iteration   3: 4.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.409 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (4.365, 4.409, 4.470), stdev = 0.054
  CI (99.9%): [3.417, 5.400] (assumes normal distribution)


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
# Warmup Iteration   1: 7.937 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 6.278 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.773 ±(99.9%) 0.022 ms/op
Iteration   1: 5.828 ±(99.9%) 0.020 ms/op
Iteration   2: 5.894 ±(99.9%) 0.029 ms/op
Iteration   3: 5.891 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.871 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (5.828, 5.871, 5.894), stdev = 0.037
  CI (99.9%): [5.195, 6.548] (assumes normal distribution)


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
# Warmup Iteration   1: 7.027 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.734 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.593 ±(99.9%) 0.016 ms/op
Iteration   1: 4.437 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.759 ms/op
                 createUser·p0.95:   6.357 ms/op
                 createUser·p0.99:   8.667 ms/op
                 createUser·p0.999:  13.337 ms/op
                 createUser·p0.9999: 16.934 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   2: 4.539 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.825 ms/op
                 createUser·p0.95:   6.521 ms/op
                 createUser·p0.99:   8.634 ms/op
                 createUser·p0.999:  13.730 ms/op
                 createUser·p0.9999: 22.314 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   3: 4.458 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.734 ms/op
                 createUser·p0.95:   6.390 ms/op
                 createUser·p0.99:   8.348 ms/op
                 createUser·p0.999:  12.967 ms/op
                 createUser·p0.9999: 25.842 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214362
  mean =      4.478 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2801 
    [ 2.500,  5.000) = 160385 
    [ 5.000,  7.500) = 46922 
    [ 7.500, 10.000) = 3441 
    [10.000, 12.500) = 511 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.767 ms/op
     p(95.0000) =      6.423 ms/op
     p(99.0000) =      8.509 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     23.237 ms/op
     p(99.9990) =     26.898 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 6.503 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.589 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.346 ±(99.9%) 0.015 ms/op
Iteration   1: 4.432 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   6.496 ms/op
                 existUser·p0.99:   8.503 ms/op
                 existUser·p0.999:  13.039 ms/op
                 existUser·p0.9999: 16.630 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 4.406 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.874 ms/op
                 existUser·p0.95:   6.627 ms/op
                 existUser·p0.99:   8.849 ms/op
                 existUser·p0.999:  14.112 ms/op
                 existUser·p0.9999: 21.747 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   3: 4.198 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   4.010 ms/op
                 existUser·p0.90:   5.497 ms/op
                 existUser·p0.95:   6.169 ms/op
                 existUser·p0.99:   8.606 ms/op
                 existUser·p0.999:  13.250 ms/op
                 existUser·p0.9999: 28.034 ms/op
                 existUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 221132
  mean =      4.342 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7945 
    [ 2.500,  5.000) = 165688 
    [ 5.000,  7.500) = 42632 
    [ 7.500, 10.000) = 3906 
    [10.000, 12.500) = 643 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      4.153 ms/op
     p(90.0000) =      5.734 ms/op
     p(95.0000) =      6.439 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     26.080 ms/op
     p(99.9990) =     29.408 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 7.140 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.873 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.603 ±(99.9%) 0.015 ms/op
Iteration   1: 4.479 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.874 ms/op
                 getUser·p0.95:   6.562 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  11.567 ms/op
                 getUser·p0.9999: 15.705 ms/op
                 getUser·p1.00:   16.073 ms/op

Iteration   2: 4.493 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.775 ms/op
                 getUser·p0.95:   6.349 ms/op
                 getUser·p0.99:   8.118 ms/op
                 getUser·p0.999:  10.870 ms/op
                 getUser·p0.9999: 23.617 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 4.583 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.898 ms/op
                 getUser·p0.95:   6.480 ms/op
                 getUser·p0.99:   8.036 ms/op
                 getUser·p0.999:  12.387 ms/op
                 getUser·p0.9999: 21.824 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 212403
  mean =      4.518 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3243 
    [ 2.500,  5.000) = 153278 
    [ 5.000,  7.500) = 51990 
    [ 7.500, 10.000) = 3344 
    [10.000, 12.500) = 415 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.849 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      8.233 ms/op
     p(99.9000) =     11.577 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     23.978 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 8.299 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.041 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.845 ±(99.9%) 0.025 ms/op
Iteration   1: 5.875 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.518 ms/op
                 listUser·p0.50:   5.480 ms/op
                 listUser·p0.90:   8.241 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 20.725 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 5.894 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   5.399 ms/op
                 listUser·p0.90:   8.290 ms/op
                 listUser·p0.95:   9.585 ms/op
                 listUser·p0.99:   12.780 ms/op
                 listUser·p0.999:  20.218 ms/op
                 listUser·p0.9999: 34.996 ms/op
                 listUser·p1.00:   35.521 ms/op

Iteration   3: 5.890 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   8.167 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   11.665 ms/op
                 listUser·p0.999:  29.675 ms/op
                 listUser·p0.9999: 40.239 ms/op
                 listUser·p1.00:   40.632 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 163157
  mean =      5.887 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 57726 
    [ 5.000, 10.000) = 99823 
    [10.000, 15.000) = 5111 
    [15.000, 20.000) = 327 
    [20.000, 25.000) = 42 
    [25.000, 30.000) = 51 
    [30.000, 35.000) = 41 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      8.233 ms/op
     p(95.0000) =      9.388 ms/op
     p(99.0000) =     12.108 ms/op
     p(99.9000) =     20.208 ms/op
     p(99.9900) =     39.149 ms/op
     p(99.9990) =     40.632 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.800 ± 1.109  ops/ms
ClientGrpc.existUser                       thrpt       3   7.365 ± 2.485  ops/ms
ClientGrpc.getUser                         thrpt       3   7.001 ± 0.433  ops/ms
ClientGrpc.listUser                        thrpt       3   5.450 ± 1.161  ops/ms
ClientGrpc.createUser                       avgt       3   4.723 ± 1.700   ms/op
ClientGrpc.existUser                        avgt       3   4.291 ± 2.287   ms/op
ClientGrpc.getUser                          avgt       3   4.409 ± 0.992   ms/op
ClientGrpc.listUser                         avgt       3   5.871 ± 0.677   ms/op
ClientGrpc.createUser                     sample  214362   4.478 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.633           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.767           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.423           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.509           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.468           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.237           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.935           ms/op
ClientGrpc.existUser                      sample  221132   4.342 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.852           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.734           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.439           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.651           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.353           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.080           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.638           ms/op
ClientGrpc.getUser                        sample  212403   4.518 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.870           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.849           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.463           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.233           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.577           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.660           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.084           ms/op
ClientGrpc.listUser                       sample  163157   5.887 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.518           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.233           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.388           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.108           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.208           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          39.149           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.632           ms/op
