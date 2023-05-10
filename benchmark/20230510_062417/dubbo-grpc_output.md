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
# Warmup Iteration   2: 9.250 ops/ms
# Warmup Iteration   3: 10.195 ops/ms
Iteration   1: 10.626 ops/ms
Iteration   2: 10.782 ops/ms
Iteration   3: 11.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.873 ±(99.9%) 5.513 ops/ms [Average]
  (min, avg, max) = (10.626, 10.873, 11.210), stdev = 0.302
  CI (99.9%): [5.359, 16.386] (assumes normal distribution)


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
# Warmup Iteration   1: 8.031 ops/ms
# Warmup Iteration   2: 10.784 ops/ms
# Warmup Iteration   3: 11.337 ops/ms
Iteration   1: 11.711 ops/ms
Iteration   2: 11.344 ops/ms
Iteration   3: 11.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.489 ±(99.9%) 3.560 ops/ms [Average]
  (min, avg, max) = (11.344, 11.489, 11.711), stdev = 0.195
  CI (99.9%): [7.929, 15.049] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.972 ops/ms
# Warmup Iteration   2: 10.389 ops/ms
# Warmup Iteration   3: 10.155 ops/ms
Iteration   1: 9.051 ops/ms
Iteration   2: 9.418 ops/ms
Iteration   3: 9.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.360 ±(99.9%) 5.181 ops/ms [Average]
  (min, avg, max) = (9.051, 9.360, 9.610), stdev = 0.284
  CI (99.9%): [4.179, 14.541] (assumes normal distribution)


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
# Warmup Iteration   1: 6.182 ops/ms
# Warmup Iteration   2: 8.150 ops/ms
# Warmup Iteration   3: 8.135 ops/ms
Iteration   1: 8.299 ops/ms
Iteration   2: 8.314 ops/ms
Iteration   3: 8.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.322 ±(99.9%) 0.494 ops/ms [Average]
  (min, avg, max) = (8.299, 8.322, 8.352), stdev = 0.027
  CI (99.9%): [7.828, 8.816] (assumes normal distribution)


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
# Warmup Iteration   1: 4.022 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
Iteration   1: 2.950 ±(99.9%) 0.002 ms/op
Iteration   2: 2.977 ±(99.9%) 0.003 ms/op
Iteration   3: 3.010 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.979 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (2.950, 2.979, 3.010), stdev = 0.030
  CI (99.9%): [2.430, 3.529] (assumes normal distribution)


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
# Warmup Iteration   1: 3.702 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.921 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.841 ±(99.9%) 0.002 ms/op
Iteration   1: 2.901 ±(99.9%) 0.003 ms/op
Iteration   2: 2.955 ±(99.9%) 0.003 ms/op
Iteration   3: 2.815 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 1.284 ms/op [Average]
  (min, avg, max) = (2.815, 2.891, 2.955), stdev = 0.070
  CI (99.9%): [1.606, 4.175] (assumes normal distribution)


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.002 ms/op
Iteration   1: 2.922 ±(99.9%) 0.002 ms/op
Iteration   2: 2.942 ±(99.9%) 0.004 ms/op
Iteration   3: 2.946 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.937 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (2.922, 2.937, 2.946), stdev = 0.013
  CI (99.9%): [2.704, 3.170] (assumes normal distribution)


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.029 ms/op
Iteration   1: 3.792 ±(99.9%) 0.016 ms/op
Iteration   2: 3.735 ±(99.9%) 0.006 ms/op
Iteration   3: 3.801 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.776 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (3.735, 3.776, 3.801), stdev = 0.036
  CI (99.9%): [3.123, 4.428] (assumes normal distribution)


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 2.943 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.182 ms/op
                 createUser·p0.999:  6.021 ms/op
                 createUser·p0.9999: 11.688 ms/op
                 createUser·p1.00:   11.993 ms/op

Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.549 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.229 ms/op
                 createUser·p0.9999: 14.998 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  12.546 ms/op
                 createUser·p0.9999: 17.733 ms/op
                 createUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324789
  mean =      2.954 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1628 
    [ 1.250,  2.500) = 27817 
    [ 2.500,  3.750) = 284074 
    [ 3.750,  5.000) = 10032 
    [ 5.000,  6.250) = 727 
    [ 6.250,  7.500) = 232 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 76 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.055 ms/op
     p(99.9900) =     16.173 ms/op
     p(99.9990) =     18.064 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 3.383 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.919 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
Iteration   1: 2.910 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.475 ms/op
                 existUser·p0.999:  6.637 ms/op
                 existUser·p0.9999: 11.895 ms/op
                 existUser·p1.00:   12.124 ms/op

Iteration   2: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.559 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.828 ms/op
                 existUser·p0.9999: 20.414 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   3: 2.875 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  8.336 ms/op
                 existUser·p0.9999: 25.260 ms/op
                 existUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331584
  mean =      2.894 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41160 
    [ 2.500,  5.000) = 289209 
    [ 5.000,  7.500) = 945 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.029 ms/op
     p(99.9900) =     20.782 ms/op
     p(99.9990) =     25.571 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
Iteration   1: 2.948 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  5.759 ms/op
                 getUser·p0.9999: 11.490 ms/op
                 getUser·p1.00:   11.682 ms/op

Iteration   2: 2.953 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.021 ms/op
                 getUser·p0.9999: 14.718 ms/op
                 getUser·p1.00:   17.859 ms/op

Iteration   3: 2.966 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   4.084 ms/op
                 getUser·p0.999:  6.457 ms/op
                 getUser·p0.9999: 14.942 ms/op
                 getUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324726
  mean =      2.956 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1543 
    [ 1.250,  2.500) = 21531 
    [ 2.500,  3.750) = 292348 
    [ 3.750,  5.000) = 8287 
    [ 5.000,  6.250) = 674 
    [ 6.250,  7.500) = 157 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.300 ms/op
     p(99.9900) =     14.729 ms/op
     p(99.9990) =     17.328 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.816 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.011 ms/op
Iteration   1: 3.954 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  12.337 ms/op
                 listUser·p0.9999: 14.598 ms/op
                 listUser·p1.00:   14.959 ms/op

Iteration   2: 3.815 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.668 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  15.873 ms/op
                 listUser·p0.9999: 24.084 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   3: 3.796 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.304 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  20.873 ms/op
                 listUser·p0.9999: 25.166 ms/op
                 listUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249221
  mean =      3.854 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5220 
    [ 2.500,  5.000) = 222379 
    [ 5.000,  7.500) = 20376 
    [ 7.500, 10.000) = 718 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.304 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     14.320 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     27.969 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.873 ± 5.513  ops/ms
ClientGrpc.existUser                       thrpt       3  11.489 ± 3.560  ops/ms
ClientGrpc.getUser                         thrpt       3   9.360 ± 5.181  ops/ms
ClientGrpc.listUser                        thrpt       3   8.322 ± 0.494  ops/ms
ClientGrpc.createUser                       avgt       3   2.979 ± 0.549   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 1.284   ms/op
ClientGrpc.getUser                          avgt       3   2.937 ± 0.233   ms/op
ClientGrpc.listUser                         avgt       3   3.776 ± 0.653   ms/op
ClientGrpc.createUser                     sample  324789   2.954 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.549           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.945           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.424           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.055           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.173           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.252           ms/op
ClientGrpc.existUser                      sample  331584   2.894 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.559           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.029           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.782           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.821           ms/op
ClientGrpc.getUser                        sample  324726   2.956 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.579           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.387           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.300           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.729           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.859           ms/op
ClientGrpc.listUser                       sample  249221   3.854 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.304           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.320           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.871           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.180           ms/op
