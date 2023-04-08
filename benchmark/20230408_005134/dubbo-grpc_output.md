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
# Warmup Iteration   1: 4.252 ops/ms
# Warmup Iteration   2: 9.208 ops/ms
# Warmup Iteration   3: 10.238 ops/ms
Iteration   1: 10.452 ops/ms
Iteration   2: 10.800 ops/ms
Iteration   3: 10.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.595 ±(99.9%) 3.313 ops/ms [Average]
  (min, avg, max) = (10.452, 10.595, 10.800), stdev = 0.182
  CI (99.9%): [7.282, 13.908] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.434 ops/ms
# Warmup Iteration   2: 10.470 ops/ms
# Warmup Iteration   3: 10.852 ops/ms
Iteration   1: 11.055 ops/ms
Iteration   2: 11.010 ops/ms
Iteration   3: 11.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.088 ±(99.9%) 1.804 ops/ms [Average]
  (min, avg, max) = (11.010, 11.088, 11.200), stdev = 0.099
  CI (99.9%): [9.284, 12.893] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.890 ops/ms
# Warmup Iteration   2: 10.366 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.784 ops/ms
Iteration   2: 10.627 ops/ms
Iteration   3: 10.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.668 ±(99.9%) 1.875 ops/ms [Average]
  (min, avg, max) = (10.591, 10.668, 10.784), stdev = 0.103
  CI (99.9%): [8.793, 12.542] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.416 ops/ms
# Warmup Iteration   2: 7.855 ops/ms
# Warmup Iteration   3: 7.995 ops/ms
Iteration   1: 8.233 ops/ms
Iteration   2: 7.993 ops/ms
Iteration   3: 8.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.102 ±(99.9%) 2.210 ops/ms [Average]
  (min, avg, max) = (7.993, 8.102, 8.233), stdev = 0.121
  CI (99.9%): [5.892, 10.312] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.249 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.012 ms/op
Iteration   1: 3.025 ±(99.9%) 0.002 ms/op
Iteration   2: 3.004 ±(99.9%) 0.003 ms/op
Iteration   3: 2.935 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.988 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (2.935, 2.988, 3.025), stdev = 0.047
  CI (99.9%): [2.132, 3.843] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.002 ms/op
Iteration   1: 2.978 ±(99.9%) 0.002 ms/op
Iteration   2: 2.861 ±(99.9%) 0.002 ms/op
Iteration   3: 2.938 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.925 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (2.861, 2.925, 2.978), stdev = 0.060
  CI (99.9%): [1.835, 4.016] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.419 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.002 ms/op
Iteration   1: 3.078 ±(99.9%) 0.004 ms/op
Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
Iteration   3: 3.041 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.057 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (3.041, 3.057, 3.078), stdev = 0.019
  CI (99.9%): [2.708, 3.405] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.355 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.015 ms/op
Iteration   1: 3.952 ±(99.9%) 0.032 ms/op
Iteration   2: 3.968 ±(99.9%) 0.012 ms/op
Iteration   3: 4.012 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.977 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (3.952, 3.977, 4.012), stdev = 0.031
  CI (99.9%): [3.405, 4.549] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.493 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.007 ms/op
Iteration   1: 3.055 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  8.031 ms/op
                 createUser·p0.9999: 18.400 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   2: 3.028 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.622 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  6.622 ms/op
                 createUser·p0.9999: 13.351 ms/op
                 createUser·p1.00:   14.991 ms/op

Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.698 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  9.486 ms/op
                 createUser·p0.9999: 16.761 ms/op
                 createUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316372
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 570 
    [ 1.250,  2.500) = 19355 
    [ 2.500,  3.750) = 282839 
    [ 3.750,  5.000) = 12087 
    [ 5.000,  6.250) = 790 
    [ 6.250,  7.500) = 262 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.628 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     18.607 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.879 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.917 ±(99.9%) 0.005 ms/op
Iteration   1: 2.825 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   4.171 ms/op
                 existUser·p0.999:  6.626 ms/op
                 existUser·p0.9999: 12.026 ms/op
                 existUser·p1.00:   12.288 ms/op

Iteration   2: 2.949 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.557 ms/op
                 existUser·p0.9999: 14.584 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   3: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.099 ms/op
                 existUser·p0.9999: 18.417 ms/op
                 existUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331632
  mean =      2.896 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2122 
    [ 1.250,  2.500) = 36319 
    [ 2.500,  3.750) = 284426 
    [ 3.750,  5.000) = 7765 
    [ 5.000,  6.250) = 530 
    [ 6.250,  7.500) = 192 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.791 ms/op
     p(99.9900) =     16.687 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.391 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.620 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  9.127 ms/op
                 getUser·p0.9999: 13.320 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.590 ms/op
                 getUser·p0.9999: 17.625 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   3: 3.030 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.205 ms/op
                 getUser·p0.9999: 16.342 ms/op
                 getUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316426
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 578 
    [ 1.250,  2.500) = 17192 
    [ 2.500,  3.750) = 282776 
    [ 3.750,  5.000) = 14481 
    [ 5.000,  6.250) = 881 
    [ 6.250,  7.500) = 178 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.307 ms/op
     p(99.9900) =     16.237 ms/op
     p(99.9990) =     17.881 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 5.697 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.011 ms/op
Iteration   1: 3.987 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.724 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   7.060 ms/op
                 listUser·p0.999:  13.795 ms/op
                 listUser·p0.9999: 15.924 ms/op
                 listUser·p1.00:   16.155 ms/op

Iteration   2: 3.909 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  16.284 ms/op
                 listUser·p0.9999: 22.467 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 3.943 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.475 ms/op
                 listUser·p0.9999: 19.027 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243138
  mean =      3.946 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1447 
    [ 2.500,  5.000) = 222681 
    [ 5.000,  7.500) = 17688 
    [ 7.500, 10.000) = 835 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     20.885 ms/op
     p(99.9990) =     23.270 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.595 ± 3.313  ops/ms
ClientGrpc.existUser                       thrpt       3  11.088 ± 1.804  ops/ms
ClientGrpc.getUser                         thrpt       3  10.668 ± 1.875  ops/ms
ClientGrpc.listUser                        thrpt       3   8.102 ± 2.210  ops/ms
ClientGrpc.createUser                       avgt       3   2.988 ± 0.856   ms/op
ClientGrpc.existUser                        avgt       3   2.925 ± 1.090   ms/op
ClientGrpc.getUser                          avgt       3   3.057 ± 0.349   ms/op
ClientGrpc.listUser                         avgt       3   3.977 ± 0.572   ms/op
ClientGrpc.createUser                     sample  316372   3.032 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.622           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.628           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.859           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.711           ms/op
ClientGrpc.existUser                      sample  331632   2.896 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.716           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.791           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.687           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.481           ms/op
ClientGrpc.getUser                        sample  316426   3.032 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.620           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.307           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.237           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.924           ms/op
ClientGrpc.listUser                       sample  243138   3.946 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.959           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.746           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.885           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.396           ms/op
