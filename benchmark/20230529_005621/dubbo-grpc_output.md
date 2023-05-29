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
# Warmup Iteration   1: 4.292 ops/ms
# Warmup Iteration   2: 9.070 ops/ms
# Warmup Iteration   3: 9.993 ops/ms
Iteration   1: 10.453 ops/ms
Iteration   2: 10.543 ops/ms
Iteration   3: 10.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.548 ±(99.9%) 1.776 ops/ms [Average]
  (min, avg, max) = (10.453, 10.548, 10.647), stdev = 0.097
  CI (99.9%): [8.771, 12.324] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.212 ops/ms
# Warmup Iteration   2: 10.475 ops/ms
# Warmup Iteration   3: 10.942 ops/ms
Iteration   1: 10.938 ops/ms
Iteration   2: 10.989 ops/ms
Iteration   3: 11.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.976 ±(99.9%) 0.599 ops/ms [Average]
  (min, avg, max) = (10.938, 10.976, 11.000), stdev = 0.033
  CI (99.9%): [10.377, 11.575] (assumes normal distribution)


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
# Warmup Iteration   1: 7.205 ops/ms
# Warmup Iteration   2: 10.255 ops/ms
# Warmup Iteration   3: 10.420 ops/ms
Iteration   1: 10.354 ops/ms
Iteration   2: 10.409 ops/ms
Iteration   3: 10.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.380 ±(99.9%) 0.503 ops/ms [Average]
  (min, avg, max) = (10.354, 10.380, 10.409), stdev = 0.028
  CI (99.9%): [9.877, 10.883] (assumes normal distribution)


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
# Warmup Iteration   1: 5.857 ops/ms
# Warmup Iteration   2: 7.477 ops/ms
# Warmup Iteration   3: 7.933 ops/ms
Iteration   1: 8.113 ops/ms
Iteration   2: 8.096 ops/ms
Iteration   3: 7.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.033 ±(99.9%) 2.261 ops/ms [Average]
  (min, avg, max) = (7.890, 8.033, 8.113), stdev = 0.124
  CI (99.9%): [5.772, 10.294] (assumes normal distribution)


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.003 ms/op
Iteration   1: 3.091 ±(99.9%) 0.001 ms/op
Iteration   2: 3.066 ±(99.9%) 0.002 ms/op
Iteration   3: 3.075 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.077 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (3.066, 3.077, 3.091), stdev = 0.012
  CI (99.9%): [2.850, 3.304] (assumes normal distribution)


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.002 ms/op
Iteration   1: 2.877 ±(99.9%) 0.002 ms/op
Iteration   2: 2.887 ±(99.9%) 0.002 ms/op
Iteration   3: 2.917 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 0.378 ms/op [Average]
  (min, avg, max) = (2.877, 2.894, 2.917), stdev = 0.021
  CI (99.9%): [2.516, 3.272] (assumes normal distribution)


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
# Warmup Iteration   1: 4.322 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.004 ms/op
Iteration   1: 3.037 ±(99.9%) 0.004 ms/op
Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
Iteration   3: 3.032 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.050 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (3.032, 3.050, 3.082), stdev = 0.027
  CI (99.9%): [2.550, 3.550] (assumes normal distribution)


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
# Warmup Iteration   1: 5.566 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.030 ms/op
Iteration   1: 4.068 ±(99.9%) 0.016 ms/op
Iteration   2: 3.989 ±(99.9%) 0.012 ms/op
Iteration   3: 4.032 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.030 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (3.989, 4.030, 4.068), stdev = 0.039
  CI (99.9%): [3.312, 4.747] (assumes normal distribution)


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
# Warmup Iteration   1: 4.309 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  8.174 ms/op
                 createUser·p0.9999: 16.668 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 3.039 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  10.789 ms/op
                 createUser·p0.9999: 29.064 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   3: 3.028 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.526 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.811 ms/op
                 createUser·p0.9999: 22.348 ms/op
                 createUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316543
  mean =      3.032 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24621 
    [ 2.500,  5.000) = 289892 
    [ 5.000,  7.500) = 1462 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      8.682 ms/op
     p(99.9900) =     28.094 ms/op
     p(99.9990) =     29.393 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.008 ms/op
Iteration   1: 3.034 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.304 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  8.789 ms/op
                 existUser·p0.9999: 15.195 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   2: 3.172 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   7.012 ms/op
                 existUser·p0.999:  9.689 ms/op
                 existUser·p0.9999: 19.355 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   3: 3.100 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   6.787 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 27.974 ms/op
                 existUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 309550
  mean =      3.101 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25537 
    [ 2.500,  5.000) = 276670 
    [ 5.000,  7.500) = 5691 
    [ 7.500, 10.000) = 1289 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.304 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     10.584 ms/op
     p(99.9900) =     27.068 ms/op
     p(99.9990) =     28.439 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.011 ms/op
Iteration   1: 3.164 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  12.237 ms/op
                 getUser·p0.9999: 16.505 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.974 ms/op
                 getUser·p0.999:  8.229 ms/op
                 getUser·p0.9999: 17.325 ms/op
                 getUser·p1.00:   17.891 ms/op

Iteration   3: 3.214 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  11.272 ms/op
                 getUser·p0.9999: 23.530 ms/op
                 getUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303376
  mean =      3.164 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23288 
    [ 2.500,  5.000) = 274289 
    [ 5.000,  7.500) = 4324 
    [ 7.500, 10.000) = 1070 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     24.008 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 6.188 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.292 ±(99.9%) 0.018 ms/op
Iteration   1: 4.292 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.570 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  15.390 ms/op
                 listUser·p0.9999: 19.220 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   2: 4.069 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.110 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  18.442 ms/op
                 listUser·p0.9999: 24.773 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   3: 3.913 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  16.882 ms/op
                 listUser·p0.9999: 19.622 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234921
  mean =      4.086 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2915 
    [ 2.500,  5.000) = 199511 
    [ 5.000,  7.500) = 29582 
    [ 7.500, 10.000) = 2120 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     24.298 ms/op
     p(99.9990) =     24.991 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.548 ± 1.776  ops/ms
ClientGrpc.existUser                       thrpt       3  10.976 ± 0.599  ops/ms
ClientGrpc.getUser                         thrpt       3  10.380 ± 0.503  ops/ms
ClientGrpc.listUser                        thrpt       3   8.033 ± 2.261  ops/ms
ClientGrpc.createUser                       avgt       3   3.077 ± 0.227   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 0.378   ms/op
ClientGrpc.getUser                          avgt       3   3.050 ± 0.500   ms/op
ClientGrpc.listUser                         avgt       3   4.030 ± 0.717   ms/op
ClientGrpc.createUser                     sample  316543   3.032 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.526           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.682           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.094           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.458           ms/op
ClientGrpc.existUser                      sample  309550   3.101 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.304           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.595           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.584           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.068           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.196           ms/op
ClientGrpc.getUser                        sample  303376   3.164 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.660           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.149           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.234           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.272           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.446           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.690           ms/op
ClientGrpc.listUser                       sample  234921   4.086 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.936           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.177           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.741           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.433           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.298           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.035           ms/op
