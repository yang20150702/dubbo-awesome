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
# Warmup Iteration   1: 4.109 ops/ms
# Warmup Iteration   2: 9.033 ops/ms
# Warmup Iteration   3: 10.061 ops/ms
Iteration   1: 10.409 ops/ms
Iteration   2: 10.546 ops/ms
Iteration   3: 10.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.497 ±(99.9%) 1.400 ops/ms [Average]
  (min, avg, max) = (10.409, 10.497, 10.546), stdev = 0.077
  CI (99.9%): [9.098, 11.897] (assumes normal distribution)


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
# Warmup Iteration   1: 6.859 ops/ms
# Warmup Iteration   2: 10.670 ops/ms
# Warmup Iteration   3: 11.148 ops/ms
Iteration   1: 11.076 ops/ms
Iteration   2: 10.944 ops/ms
Iteration   3: 11.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.060 ±(99.9%) 1.972 ops/ms [Average]
  (min, avg, max) = (10.944, 11.060, 11.158), stdev = 0.108
  CI (99.9%): [9.088, 13.032] (assumes normal distribution)


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
# Warmup Iteration   1: 6.674 ops/ms
# Warmup Iteration   2: 10.229 ops/ms
# Warmup Iteration   3: 10.579 ops/ms
Iteration   1: 10.731 ops/ms
Iteration   2: 10.818 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.750 ±(99.9%) 1.108 ops/ms [Average]
  (min, avg, max) = (10.702, 10.750, 10.818), stdev = 0.061
  CI (99.9%): [9.643, 11.858] (assumes normal distribution)


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
# Warmup Iteration   1: 6.569 ops/ms
# Warmup Iteration   2: 7.656 ops/ms
# Warmup Iteration   3: 8.183 ops/ms
Iteration   1: 8.122 ops/ms
Iteration   2: 8.081 ops/ms
Iteration   3: 8.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.088 ±(99.9%) 0.568 ops/ms [Average]
  (min, avg, max) = (8.061, 8.088, 8.122), stdev = 0.031
  CI (99.9%): [7.520, 8.655] (assumes normal distribution)


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
# Warmup Iteration   1: 4.351 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.002 ms/op
Iteration   1: 3.036 ±(99.9%) 0.003 ms/op
Iteration   2: 2.997 ±(99.9%) 0.002 ms/op
Iteration   3: 3.062 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.032 ±(99.9%) 0.600 ms/op [Average]
  (min, avg, max) = (2.997, 3.032, 3.062), stdev = 0.033
  CI (99.9%): [2.431, 3.632] (assumes normal distribution)


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.002 ms/op
Iteration   1: 2.855 ±(99.9%) 0.002 ms/op
Iteration   2: 2.892 ±(99.9%) 0.002 ms/op
Iteration   3: 2.894 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.881 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (2.855, 2.881, 2.894), stdev = 0.022
  CI (99.9%): [2.476, 3.285] (assumes normal distribution)


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.003 ms/op
Iteration   1: 3.017 ±(99.9%) 0.004 ms/op
Iteration   2: 2.977 ±(99.9%) 0.005 ms/op
Iteration   3: 3.019 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.004 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.977, 3.004, 3.019), stdev = 0.023
  CI (99.9%): [2.578, 3.430] (assumes normal distribution)


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
# Warmup Iteration   1: 5.577 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.028 ms/op
Iteration   1: 3.864 ±(99.9%) 0.012 ms/op
Iteration   2: 3.954 ±(99.9%) 0.011 ms/op
Iteration   3: 3.926 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.915 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (3.864, 3.915, 3.954), stdev = 0.046
  CI (99.9%): [3.070, 4.759] (assumes normal distribution)


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
# Warmup Iteration   1: 4.262 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
Iteration   1: 2.957 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.454 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  9.500 ms/op
                 createUser·p0.9999: 12.870 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   2: 2.954 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.654 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  6.657 ms/op
                 createUser·p0.9999: 13.978 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   3: 2.971 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  10.383 ms/op
                 createUser·p0.9999: 24.198 ms/op
                 createUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324212
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35183 
    [ 2.500,  5.000) = 287048 
    [ 5.000,  7.500) = 1539 
    [ 7.500, 10.000) = 167 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.709 ms/op
     p(99.9000) =      9.430 ms/op
     p(99.9900) =     18.435 ms/op
     p(99.9990) =     24.503 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.005 ms/op
Iteration   1: 2.867 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.965 ms/op
                 existUser·p0.9999: 13.460 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  10.158 ms/op
                 existUser·p0.9999: 13.848 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   3: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.035 ms/op
                 existUser·p0.999:  6.689 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329635
  mean =      2.911 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 791 
    [ 1.250,  2.500) = 40673 
    [ 2.500,  3.750) = 280471 
    [ 3.750,  5.000) = 6442 
    [ 5.000,  6.250) = 652 
    [ 6.250,  7.500) = 174 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     14.366 ms/op
     p(99.9990) =     17.488 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  9.535 ms/op
                 getUser·p0.9999: 12.115 ms/op
                 getUser·p1.00:   12.304 ms/op

Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  6.371 ms/op
                 getUser·p0.9999: 14.434 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  6.411 ms/op
                 getUser·p0.9999: 17.826 ms/op
                 getUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317085
  mean =      3.026 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 267 
    [ 1.250,  2.500) = 25956 
    [ 2.500,  3.750) = 273690 
    [ 3.750,  5.000) = 15390 
    [ 5.000,  6.250) = 1226 
    [ 6.250,  7.500) = 260 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     17.190 ms/op
     p(99.9990) =     18.312 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.125 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.012 ms/op
Iteration   1: 3.927 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.764 ms/op
                 listUser·p0.999:  13.526 ms/op
                 listUser·p0.9999: 21.852 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   2: 3.892 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  13.856 ms/op
                 listUser·p0.9999: 18.065 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   3: 3.881 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  15.701 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246097
  mean =      3.900 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2848 
    [ 2.500,  5.000) = 221829 
    [ 5.000,  7.500) = 20386 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.702 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     22.260 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.497 ± 1.400  ops/ms
ClientGrpc.existUser                       thrpt       3  11.060 ± 1.972  ops/ms
ClientGrpc.getUser                         thrpt       3  10.750 ± 1.108  ops/ms
ClientGrpc.listUser                        thrpt       3   8.088 ± 0.568  ops/ms
ClientGrpc.createUser                       avgt       3   3.032 ± 0.600   ms/op
ClientGrpc.existUser                        avgt       3   2.881 ± 0.404   ms/op
ClientGrpc.getUser                          avgt       3   3.004 ± 0.426   ms/op
ClientGrpc.listUser                         avgt       3   3.915 ± 0.844   ms/op
ClientGrpc.createUser                     sample  324212   2.961 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.561           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.445           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.709           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.430           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.435           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.576           ms/op
ClientGrpc.existUser                      sample  329635   2.911 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.625           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.962           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.366           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.498           ms/op
ClientGrpc.getUser                        sample  317085   3.026 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.593           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.963           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.190           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.383           ms/op
ClientGrpc.listUser                       sample  246097   3.900 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.067           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.702           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.594           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
