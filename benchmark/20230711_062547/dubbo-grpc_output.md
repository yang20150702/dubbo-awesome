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
# Warmup Iteration   1: 4.361 ops/ms
# Warmup Iteration   2: 9.032 ops/ms
# Warmup Iteration   3: 10.399 ops/ms
Iteration   1: 10.692 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.671 ±(99.9%) 0.820 ops/ms [Average]
  (min, avg, max) = (10.619, 10.671, 10.702), stdev = 0.045
  CI (99.9%): [9.851, 11.491] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.026 ops/ms
# Warmup Iteration   2: 10.792 ops/ms
# Warmup Iteration   3: 10.958 ops/ms
Iteration   1: 11.173 ops/ms
Iteration   2: 11.247 ops/ms
Iteration   3: 11.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.247 ±(99.9%) 1.342 ops/ms [Average]
  (min, avg, max) = (11.173, 11.247, 11.320), stdev = 0.074
  CI (99.9%): [9.905, 12.589] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.793 ops/ms
# Warmup Iteration   2: 10.367 ops/ms
# Warmup Iteration   3: 10.793 ops/ms
Iteration   1: 10.683 ops/ms
Iteration   2: 10.749 ops/ms
Iteration   3: 10.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.716 ±(99.9%) 0.602 ops/ms [Average]
  (min, avg, max) = (10.683, 10.716, 10.749), stdev = 0.033
  CI (99.9%): [10.114, 11.318] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.842 ops/ms
# Warmup Iteration   2: 8.150 ops/ms
# Warmup Iteration   3: 8.397 ops/ms
Iteration   1: 8.317 ops/ms
Iteration   2: 8.209 ops/ms
Iteration   3: 8.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.283 ±(99.9%) 1.166 ops/ms [Average]
  (min, avg, max) = (8.209, 8.283, 8.323), stdev = 0.064
  CI (99.9%): [7.117, 9.449] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.990 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.003 ms/op
Iteration   1: 3.075 ±(99.9%) 0.002 ms/op
Iteration   2: 2.995 ±(99.9%) 0.003 ms/op
Iteration   3: 3.014 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.028 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (2.995, 3.028, 3.075), stdev = 0.042
  CI (99.9%): [2.266, 3.790] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.962 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.002 ms/op
Iteration   1: 2.888 ±(99.9%) 0.005 ms/op
Iteration   2: 2.907 ±(99.9%) 0.003 ms/op
Iteration   3: 2.933 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.909 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.888, 2.909, 2.933), stdev = 0.023
  CI (99.9%): [2.497, 3.321] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 3.053 ±(99.9%) 0.003 ms/op
Iteration   2: 3.008 ±(99.9%) 0.002 ms/op
Iteration   3: 2.976 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.012 ±(99.9%) 0.707 ms/op [Average]
  (min, avg, max) = (2.976, 3.012, 3.053), stdev = 0.039
  CI (99.9%): [2.305, 3.719] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.074 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.011 ms/op
Iteration   1: 3.792 ±(99.9%) 0.039 ms/op
Iteration   2: 3.780 ±(99.9%) 0.028 ms/op
Iteration   3: 3.813 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.795 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (3.780, 3.795, 3.813), stdev = 0.017
  CI (99.9%): [3.493, 4.097] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  11.796 ms/op
                 createUser·p0.9999: 15.417 ms/op
                 createUser·p1.00:   15.614 ms/op

Iteration   2: 2.972 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.609 ms/op
                 createUser·p0.9999: 20.694 ms/op
                 createUser·p1.00:   33.554 ms/op

Iteration   3: 3.007 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.507 ms/op
                 createUser·p0.999:  6.709 ms/op
                 createUser·p0.9999: 22.392 ms/op
                 createUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319756
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28523 
    [ 2.500,  5.000) = 289877 
    [ 5.000,  7.500) = 1017 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.073 ms/op
     p(99.9900) =     21.890 ms/op
     p(99.9990) =     32.789 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.005 ms/op
Iteration   1: 2.872 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.167 ms/op
                 existUser·p0.999:  8.399 ms/op
                 existUser·p0.9999: 16.420 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   2: 2.853 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.493 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  5.421 ms/op
                 existUser·p0.9999: 12.608 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   3: 2.901 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  8.102 ms/op
                 existUser·p0.9999: 15.106 ms/op
                 existUser·p1.00:   15.434 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333868
  mean =      2.875 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2178 
    [ 1.250,  2.500) = 43351 
    [ 2.500,  3.750) = 278784 
    [ 3.750,  5.000) = 8610 
    [ 5.000,  6.250) = 533 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.024 ms/op
     p(99.9900) =     15.415 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.837 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.798 ms/op
                 getUser·p0.9999: 17.801 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.479 ms/op
                 getUser·p0.9999: 17.052 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   3: 3.003 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.373 ms/op
                 getUser·p0.9999: 13.637 ms/op
                 getUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320497
  mean =      2.995 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1589 
    [ 1.250,  2.500) = 27119 
    [ 2.500,  3.750) = 279046 
    [ 3.750,  5.000) = 11738 
    [ 5.000,  6.250) = 533 
    [ 6.250,  7.500) = 217 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.910 ms/op
     p(99.9900) =     17.333 ms/op
     p(99.9990) =     19.186 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 4.969 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.010 ms/op
Iteration   1: 3.802 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  12.452 ms/op
                 listUser·p0.9999: 13.608 ms/op
                 listUser·p1.00:   14.746 ms/op

Iteration   2: 3.869 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.346 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  14.243 ms/op
                 listUser·p0.9999: 23.870 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   3: 3.864 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.641 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 15.903 ms/op
                 listUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249497
  mean =      3.845 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3831 
    [ 2.500,  5.000) = 225913 
    [ 5.000,  7.500) = 18752 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     13.435 ms/op
     p(99.9900) =     22.744 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.671 ± 0.820  ops/ms
ClientGrpc.existUser                       thrpt       3  11.247 ± 1.342  ops/ms
ClientGrpc.getUser                         thrpt       3  10.716 ± 0.602  ops/ms
ClientGrpc.listUser                        thrpt       3   8.283 ± 1.166  ops/ms
ClientGrpc.createUser                       avgt       3   3.028 ± 0.762   ms/op
ClientGrpc.existUser                        avgt       3   2.909 ± 0.412   ms/op
ClientGrpc.getUser                          avgt       3   3.012 ± 0.707   ms/op
ClientGrpc.listUser                         avgt       3   3.795 ± 0.302   ms/op
ClientGrpc.createUser                     sample  319756   2.998 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.574           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.073           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.890           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.554           ms/op
ClientGrpc.existUser                      sample  333868   2.875 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.493           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.024           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.415           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.400           ms/op
ClientGrpc.getUser                        sample  320497   2.995 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.682           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.910           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.333           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.431           ms/op
ClientGrpc.listUser                       sample  249497   3.845 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.038           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.707           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.627           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.435           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.744           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.412           ms/op
