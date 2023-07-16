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
# Warmup Iteration   1: 4.126 ops/ms
# Warmup Iteration   2: 9.070 ops/ms
# Warmup Iteration   3: 10.061 ops/ms
Iteration   1: 10.370 ops/ms
Iteration   2: 10.679 ops/ms
Iteration   3: 10.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.554 ±(99.9%) 2.969 ops/ms [Average]
  (min, avg, max) = (10.370, 10.554, 10.679), stdev = 0.163
  CI (99.9%): [7.585, 13.523] (assumes normal distribution)


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
# Warmup Iteration   1: 7.523 ops/ms
# Warmup Iteration   2: 10.593 ops/ms
# Warmup Iteration   3: 11.118 ops/ms
Iteration   1: 10.959 ops/ms
Iteration   2: 11.104 ops/ms
Iteration   3: 11.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.028 ±(99.9%) 1.324 ops/ms [Average]
  (min, avg, max) = (10.959, 11.028, 11.104), stdev = 0.073
  CI (99.9%): [9.703, 12.352] (assumes normal distribution)


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
# Warmup Iteration   1: 7.318 ops/ms
# Warmup Iteration   2: 9.945 ops/ms
# Warmup Iteration   3: 10.280 ops/ms
Iteration   1: 10.332 ops/ms
Iteration   2: 10.627 ops/ms
Iteration   3: 10.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.447 ±(99.9%) 2.877 ops/ms [Average]
  (min, avg, max) = (10.332, 10.447, 10.627), stdev = 0.158
  CI (99.9%): [7.569, 13.324] (assumes normal distribution)


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
# Warmup Iteration   1: 6.195 ops/ms
# Warmup Iteration   2: 7.878 ops/ms
# Warmup Iteration   3: 8.080 ops/ms
Iteration   1: 8.221 ops/ms
Iteration   2: 8.246 ops/ms
Iteration   3: 8.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.247 ±(99.9%) 0.480 ops/ms [Average]
  (min, avg, max) = (8.221, 8.247, 8.273), stdev = 0.026
  CI (99.9%): [7.766, 8.727] (assumes normal distribution)


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.003 ms/op
Iteration   2: 3.008 ±(99.9%) 0.003 ms/op
Iteration   3: 2.983 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.007 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.983, 3.007, 3.028), stdev = 0.023
  CI (99.9%): [2.595, 3.418] (assumes normal distribution)


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.941 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.003 ms/op
Iteration   1: 2.876 ±(99.9%) 0.001 ms/op
Iteration   2: 2.915 ±(99.9%) 0.003 ms/op
Iteration   3: 2.872 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.887 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (2.872, 2.887, 2.915), stdev = 0.024
  CI (99.9%): [2.456, 3.319] (assumes normal distribution)


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.003 ms/op
Iteration   1: 3.019 ±(99.9%) 0.003 ms/op
Iteration   2: 3.004 ±(99.9%) 0.003 ms/op
Iteration   3: 2.964 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.996 ±(99.9%) 0.517 ms/op [Average]
  (min, avg, max) = (2.964, 2.996, 3.019), stdev = 0.028
  CI (99.9%): [2.478, 3.513] (assumes normal distribution)


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
# Warmup Iteration   1: 5.158 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.009 ms/op
Iteration   1: 3.918 ±(99.9%) 0.047 ms/op
Iteration   2: 3.905 ±(99.9%) 0.059 ms/op
Iteration   3: 3.892 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.905 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (3.892, 3.905, 3.918), stdev = 0.013
  CI (99.9%): [3.673, 4.136] (assumes normal distribution)


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
# Warmup Iteration   1: 3.908 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
Iteration   1: 3.019 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.154 ms/op
                 createUser·p0.9999: 12.432 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.851 ms/op
                 createUser·p0.9999: 13.393 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.578 ms/op
                 createUser·p0.9999: 18.079 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317980
  mean =      3.017 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1439 
    [ 1.250,  2.500) = 23020 
    [ 2.500,  3.750) = 276034 
    [ 3.750,  5.000) = 15922 
    [ 5.000,  6.250) = 797 
    [ 6.250,  7.500) = 396 
    [ 7.500,  8.750) = 135 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.766 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     18.672 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.005 ms/op
Iteration   1: 2.978 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.851 ms/op
                 existUser·p0.9999: 13.124 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   2: 2.968 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.054 ms/op
                 existUser·p0.9999: 19.308 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  7.464 ms/op
                 existUser·p0.9999: 16.986 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321559
  mean =      2.985 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1204 
    [ 1.250,  2.500) = 28760 
    [ 2.500,  3.750) = 277894 
    [ 3.750,  5.000) = 12441 
    [ 5.000,  6.250) = 607 
    [ 6.250,  7.500) = 372 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.294 ms/op
     p(99.9900) =     18.434 ms/op
     p(99.9990) =     19.621 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.664 ms/op
                 getUser·p0.9999: 11.476 ms/op
                 getUser·p1.00:   12.304 ms/op

Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  9.224 ms/op
                 getUser·p0.9999: 13.613 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.154 ms/op
                 getUser·p0.9999: 25.114 ms/op
                 getUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316741
  mean =      3.030 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18116 
    [ 2.500,  5.000) = 296997 
    [ 5.000,  7.500) = 1212 
    [ 7.500, 10.000) = 194 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     23.706 ms/op
     p(99.9990) =     25.390 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 5.030 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.012 ms/op
Iteration   1: 3.971 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  12.337 ms/op
                 listUser·p0.9999: 15.450 ms/op
                 listUser·p1.00:   16.056 ms/op

Iteration   2: 3.987 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 17.757 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 3.874 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243472
  mean =      3.944 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 3777 
    [ 2.500,  3.750) = 108038 
    [ 3.750,  5.000) = 109877 
    [ 5.000,  6.250) = 16416 
    [ 6.250,  7.500) = 4194 
    [ 7.500,  8.750) = 570 
    [ 8.750, 10.000) = 137 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 93 
    [16.250, 17.500) = 54 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     13.411 ms/op
     p(99.9900) =     17.180 ms/op
     p(99.9990) =     18.733 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.554 ± 2.969  ops/ms
ClientGrpc.existUser                       thrpt       3  11.028 ± 1.324  ops/ms
ClientGrpc.getUser                         thrpt       3  10.447 ± 2.877  ops/ms
ClientGrpc.listUser                        thrpt       3   8.247 ± 0.480  ops/ms
ClientGrpc.createUser                       avgt       3   3.007 ± 0.412   ms/op
ClientGrpc.existUser                        avgt       3   2.887 ± 0.432   ms/op
ClientGrpc.getUser                          avgt       3   2.996 ± 0.517   ms/op
ClientGrpc.listUser                         avgt       3   3.905 ± 0.231   ms/op
ClientGrpc.createUser                     sample  317980   3.017 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.561           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.766           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.105           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.038           ms/op
ClientGrpc.existUser                      sample  321559   2.985 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.660           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.294           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.434           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.694           ms/op
ClientGrpc.getUser                        sample  316741   3.030 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.765           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.651           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.706           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.657           ms/op
ClientGrpc.listUser                       sample  243472   3.944 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.104           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.411           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.180           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.842           ms/op
