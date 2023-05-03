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
# Warmup Iteration   1: 4.322 ops/ms
# Warmup Iteration   2: 9.318 ops/ms
# Warmup Iteration   3: 10.320 ops/ms
Iteration   1: 10.508 ops/ms
Iteration   2: 10.583 ops/ms
Iteration   3: 10.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.535 ±(99.9%) 0.751 ops/ms [Average]
  (min, avg, max) = (10.508, 10.535, 10.583), stdev = 0.041
  CI (99.9%): [9.784, 11.287] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.808 ops/ms
# Warmup Iteration   2: 10.594 ops/ms
# Warmup Iteration   3: 11.226 ops/ms
Iteration   1: 11.704 ops/ms
Iteration   2: 11.263 ops/ms
Iteration   3: 11.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.341 ±(99.9%) 6.041 ops/ms [Average]
  (min, avg, max) = (11.056, 11.341, 11.704), stdev = 0.331
  CI (99.9%): [5.300, 17.382] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.032 ops/ms
# Warmup Iteration   2: 9.799 ops/ms
# Warmup Iteration   3: 9.894 ops/ms
Iteration   1: 9.955 ops/ms
Iteration   2: 9.769 ops/ms
Iteration   3: 9.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.839 ±(99.9%) 1.841 ops/ms [Average]
  (min, avg, max) = (9.769, 9.839, 9.955), stdev = 0.101
  CI (99.9%): [7.998, 11.680] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.713 ops/ms
# Warmup Iteration   2: 7.111 ops/ms
# Warmup Iteration   3: 7.564 ops/ms
Iteration   1: 7.801 ops/ms
Iteration   2: 8.120 ops/ms
Iteration   3: 8.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.044 ±(99.9%) 3.923 ops/ms [Average]
  (min, avg, max) = (7.801, 8.044, 8.211), stdev = 0.215
  CI (99.9%): [4.121, 11.967] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.492 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.017 ms/op
Iteration   1: 3.016 ±(99.9%) 0.002 ms/op
Iteration   2: 2.945 ±(99.9%) 0.003 ms/op
Iteration   3: 3.051 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.004 ±(99.9%) 0.987 ms/op [Average]
  (min, avg, max) = (2.945, 3.004, 3.051), stdev = 0.054
  CI (99.9%): [2.017, 3.991] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.139 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.003 ms/op
Iteration   1: 2.848 ±(99.9%) 0.002 ms/op
Iteration   2: 2.863 ±(99.9%) 0.001 ms/op
Iteration   3: 2.805 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.839 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (2.805, 2.839, 2.863), stdev = 0.030
  CI (99.9%): [2.297, 3.380] (assumes normal distribution)


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.003 ms/op
Iteration   1: 3.020 ±(99.9%) 0.002 ms/op
Iteration   2: 3.017 ±(99.9%) 0.003 ms/op
Iteration   3: 3.000 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.012 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (3.000, 3.012, 3.020), stdev = 0.011
  CI (99.9%): [2.820, 3.204] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.177 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.015 ms/op
Iteration   1: 3.755 ±(99.9%) 0.005 ms/op
Iteration   2: 3.867 ±(99.9%) 0.016 ms/op
Iteration   3: 3.793 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.805 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (3.755, 3.805, 3.867), stdev = 0.057
  CI (99.9%): [2.770, 4.840] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.030 ms/op
                 createUser·p0.9999: 11.983 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  9.652 ms/op
                 createUser·p0.9999: 17.479 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   3: 3.072 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  13.295 ms/op
                 createUser·p0.9999: 17.859 ms/op
                 createUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315707
  mean =      3.039 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 451 
    [ 1.250,  2.500) = 22598 
    [ 2.500,  3.750) = 278954 
    [ 3.750,  5.000) = 11802 
    [ 5.000,  6.250) = 934 
    [ 6.250,  7.500) = 373 
    [ 7.500,  8.750) = 240 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 61 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     10.266 ms/op
     p(99.9900) =     17.447 ms/op
     p(99.9990) =     18.279 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.005 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  6.406 ms/op
                 existUser·p0.9999: 12.177 ms/op
                 existUser·p1.00:   12.386 ms/op

Iteration   2: 2.861 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   3.908 ms/op
                 existUser·p0.999:  5.818 ms/op
                 existUser·p0.9999: 20.251 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   3: 2.840 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  8.823 ms/op
                 existUser·p0.9999: 14.053 ms/op
                 existUser·p1.00:   14.287 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332172
  mean =      2.891 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36524 
    [ 2.500,  5.000) = 294591 
    [ 5.000,  7.500) = 815 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.026 ms/op
     p(99.9000) =      6.578 ms/op
     p(99.9900) =     14.283 ms/op
     p(99.9990) =     20.732 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.186 ms/op
                 getUser·p0.9999: 17.859 ms/op
                 getUser·p1.00:   18.022 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  6.267 ms/op
                 getUser·p0.9999: 18.950 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.955 ms/op
                 getUser·p0.9999: 23.082 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320387
  mean =      2.994 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24120 
    [ 2.500,  5.000) = 294725 
    [ 5.000,  7.500) = 1313 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      6.894 ms/op
     p(99.9900) =     21.191 ms/op
     p(99.9990) =     23.265 ms/op
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
# Warmup Iteration   1: 4.901 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.009 ms/op
Iteration   1: 3.908 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.028 ms/op
                 listUser·p0.9999: 14.570 ms/op
                 listUser·p1.00:   16.728 ms/op

Iteration   2: 3.907 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  16.666 ms/op
                 listUser·p0.9999: 26.202 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   3: 3.892 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 17.844 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245915
  mean =      3.902 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2918 
    [ 2.500,  5.000) = 223254 
    [ 5.000,  7.500) = 18718 
    [ 7.500, 10.000) = 575 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     13.977 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     27.120 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.535 ± 0.751  ops/ms
ClientGrpc.existUser                       thrpt       3  11.341 ± 6.041  ops/ms
ClientGrpc.getUser                         thrpt       3   9.839 ± 1.841  ops/ms
ClientGrpc.listUser                        thrpt       3   8.044 ± 3.923  ops/ms
ClientGrpc.createUser                       avgt       3   3.004 ± 0.987   ms/op
ClientGrpc.existUser                        avgt       3   2.839 ± 0.542   ms/op
ClientGrpc.getUser                          avgt       3   3.012 ± 0.192   ms/op
ClientGrpc.listUser                         avgt       3   3.805 ± 1.035   ms/op
ClientGrpc.createUser                     sample  315707   3.039 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.816           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.266           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.447           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.383           ms/op
ClientGrpc.existUser                      sample  332172   2.891 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.658           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.578           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.283           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.873           ms/op
ClientGrpc.getUser                        sample  320387   2.994 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.746           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.449           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.894           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.191           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.364           ms/op
ClientGrpc.listUser                       sample  245915   3.902 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.139           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.709           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.977           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.657           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.230           ms/op
