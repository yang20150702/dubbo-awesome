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
# Warmup Iteration   1: 3.074 ops/ms
# Warmup Iteration   2: 6.756 ops/ms
# Warmup Iteration   3: 8.360 ops/ms
Iteration   1: 8.500 ops/ms
Iteration   2: 8.527 ops/ms
Iteration   3: 8.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.500 ±(99.9%) 0.494 ops/ms [Average]
  (min, avg, max) = (8.473, 8.500, 8.527), stdev = 0.027
  CI (99.9%): [8.005, 8.994] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.942 ops/ms
# Warmup Iteration   2: 8.505 ops/ms
# Warmup Iteration   3: 9.251 ops/ms
Iteration   1: 9.073 ops/ms
Iteration   2: 9.094 ops/ms
Iteration   3: 8.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.034 ±(99.9%) 1.596 ops/ms [Average]
  (min, avg, max) = (8.933, 9.034, 9.094), stdev = 0.087
  CI (99.9%): [7.438, 10.630] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.407 ops/ms
# Warmup Iteration   2: 8.345 ops/ms
# Warmup Iteration   3: 8.652 ops/ms
Iteration   1: 8.936 ops/ms
Iteration   2: 8.776 ops/ms
Iteration   3: 8.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.832 ±(99.9%) 1.643 ops/ms [Average]
  (min, avg, max) = (8.776, 8.832, 8.936), stdev = 0.090
  CI (99.9%): [7.189, 10.475] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.117 ops/ms
# Warmup Iteration   2: 6.358 ops/ms
# Warmup Iteration   3: 6.606 ops/ms
Iteration   1: 6.715 ops/ms
Iteration   2: 6.702 ops/ms
Iteration   3: 6.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.700 ±(99.9%) 0.289 ops/ms [Average]
  (min, avg, max) = (6.684, 6.700, 6.715), stdev = 0.016
  CI (99.9%): [6.411, 6.989] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.007 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.775 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.014 ms/op
Iteration   1: 3.603 ±(99.9%) 0.002 ms/op
Iteration   2: 3.515 ±(99.9%) 0.003 ms/op
Iteration   3: 3.457 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.525 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (3.457, 3.525, 3.603), stdev = 0.074
  CI (99.9%): [2.183, 4.866] (assumes normal distribution)


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
# Warmup Iteration   1: 4.606 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.003 ms/op
Iteration   1: 3.338 ±(99.9%) 0.004 ms/op
Iteration   2: 3.278 ±(99.9%) 0.003 ms/op
Iteration   3: 3.316 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.310 ±(99.9%) 0.555 ms/op [Average]
  (min, avg, max) = (3.278, 3.310, 3.338), stdev = 0.030
  CI (99.9%): [2.755, 3.866] (assumes normal distribution)


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
# Warmup Iteration   1: 5.031 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.002 ms/op
Iteration   1: 3.363 ±(99.9%) 0.008 ms/op
Iteration   2: 3.375 ±(99.9%) 0.003 ms/op
Iteration   3: 3.384 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.374 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (3.363, 3.374, 3.384), stdev = 0.011
  CI (99.9%): [3.178, 3.570] (assumes normal distribution)


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
# Warmup Iteration   1: 6.338 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.734 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.368 ±(99.9%) 0.012 ms/op
Iteration   1: 4.471 ±(99.9%) 0.022 ms/op
Iteration   2: 4.540 ±(99.9%) 0.015 ms/op
Iteration   3: 4.352 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.454 ±(99.9%) 1.737 ms/op [Average]
  (min, avg, max) = (4.352, 4.454, 4.540), stdev = 0.095
  CI (99.9%): [2.717, 6.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.770 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.008 ms/op
Iteration   1: 3.478 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  8.834 ms/op
                 createUser·p0.9999: 23.816 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   2: 3.443 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  8.053 ms/op
                 createUser·p0.9999: 26.982 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   3: 3.333 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   5.074 ms/op
                 createUser·p0.999:  10.913 ms/op
                 createUser·p0.9999: 29.865 ms/op
                 createUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 280765
  mean =      3.417 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7560 
    [ 2.500,  5.000) = 269584 
    [ 5.000,  7.500) = 3040 
    [ 7.500, 10.000) = 352 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =      9.354 ms/op
     p(99.9900) =     29.390 ms/op
     p(99.9990) =     30.186 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 4.639 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.007 ms/op
Iteration   1: 3.397 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  7.952 ms/op
                 existUser·p0.9999: 19.207 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   2: 3.412 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  8.204 ms/op
                 existUser·p0.9999: 26.182 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   3: 3.308 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  9.808 ms/op
                 existUser·p0.9999: 18.197 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 284704
  mean =      3.372 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11864 
    [ 2.500,  5.000) = 269357 
    [ 5.000,  7.500) = 3103 
    [ 7.500, 10.000) = 174 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =      8.096 ms/op
     p(99.9900) =     25.281 ms/op
     p(99.9990) =     26.613 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 4.954 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.008 ms/op
Iteration   1: 3.449 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  7.997 ms/op
                 getUser·p0.9999: 25.654 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   2: 3.551 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  10.828 ms/op
                 getUser·p0.9999: 17.006 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   3: 3.460 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  7.990 ms/op
                 getUser·p0.9999: 20.505 ms/op
                 getUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 275290
  mean =      3.486 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9914 
    [ 2.500,  5.000) = 260016 
    [ 5.000,  7.500) = 4875 
    [ 7.500, 10.000) = 292 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      8.380 ms/op
     p(99.9900) =     24.607 ms/op
     p(99.9990) =     26.616 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 5.975 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.906 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.601 ±(99.9%) 0.015 ms/op
Iteration   1: 4.615 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.718 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  14.343 ms/op
                 listUser·p0.9999: 16.664 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   2: 4.776 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.997 ms/op
                 listUser·p0.95:   6.606 ms/op
                 listUser·p0.99:   8.319 ms/op
                 listUser·p0.999:  15.861 ms/op
                 listUser·p0.9999: 18.622 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 4.446 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  19.104 ms/op
                 listUser·p0.9999: 22.091 ms/op
                 listUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208309
  mean =      4.608 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 453 
    [ 2.500,  5.000) = 167968 
    [ 5.000,  7.500) = 36065 
    [ 7.500, 10.000) = 3259 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     15.969 ms/op
     p(99.9900) =     21.414 ms/op
     p(99.9990) =     22.375 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.500 ± 0.494  ops/ms
ClientGrpc.existUser                       thrpt       3   9.034 ± 1.596  ops/ms
ClientGrpc.getUser                         thrpt       3   8.832 ± 1.643  ops/ms
ClientGrpc.listUser                        thrpt       3   6.700 ± 0.289  ops/ms
ClientGrpc.createUser                       avgt       3   3.525 ± 1.342   ms/op
ClientGrpc.existUser                        avgt       3   3.310 ± 0.555   ms/op
ClientGrpc.getUser                          avgt       3   3.374 ± 0.196   ms/op
ClientGrpc.listUser                         avgt       3   4.454 ± 1.737   ms/op
ClientGrpc.createUser                     sample  280765   3.417 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.719           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.383           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.940           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.218           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.354           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.390           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.278           ms/op
ClientGrpc.existUser                      sample  284704   3.372 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.775           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.177           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.096           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.281           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.706           ms/op
ClientGrpc.getUser                        sample  275290   3.486 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.734           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.141           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.546           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.380           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.607           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.706           ms/op
ClientGrpc.listUser                       sample  208309   4.608 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.274           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.463           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.126           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.969           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.414           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.479           ms/op
