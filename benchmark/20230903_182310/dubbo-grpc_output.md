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
# Warmup Iteration   1: 1.960 ops/ms
# Warmup Iteration   2: 5.375 ops/ms
# Warmup Iteration   3: 7.053 ops/ms
Iteration   1: 7.308 ops/ms
Iteration   2: 7.239 ops/ms
Iteration   3: 7.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.246 ±(99.9%) 1.062 ops/ms [Average]
  (min, avg, max) = (7.192, 7.246, 7.308), stdev = 0.058
  CI (99.9%): [6.184, 8.309] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.987 ops/ms
# Warmup Iteration   2: 7.134 ops/ms
# Warmup Iteration   3: 7.597 ops/ms
Iteration   1: 7.625 ops/ms
Iteration   2: 7.666 ops/ms
Iteration   3: 7.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.649 ±(99.9%) 0.391 ops/ms [Average]
  (min, avg, max) = (7.625, 7.649, 7.666), stdev = 0.021
  CI (99.9%): [7.258, 8.040] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.685 ops/ms
# Warmup Iteration   2: 6.713 ops/ms
# Warmup Iteration   3: 7.175 ops/ms
Iteration   1: 7.335 ops/ms
Iteration   2: 7.193 ops/ms
Iteration   3: 7.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.239 ±(99.9%) 1.510 ops/ms [Average]
  (min, avg, max) = (7.190, 7.239, 7.335), stdev = 0.083
  CI (99.9%): [5.729, 8.749] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.746 ops/ms
# Warmup Iteration   2: 5.092 ops/ms
# Warmup Iteration   3: 5.648 ops/ms
Iteration   1: 5.713 ops/ms
Iteration   2: 5.579 ops/ms
Iteration   3: 5.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.711 ±(99.9%) 2.380 ops/ms [Average]
  (min, avg, max) = (5.579, 5.711, 5.840), stdev = 0.130
  CI (99.9%): [3.330, 8.091] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.066 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.793 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.493 ±(99.9%) 0.013 ms/op
Iteration   1: 4.409 ±(99.9%) 0.005 ms/op
Iteration   2: 4.440 ±(99.9%) 0.004 ms/op
Iteration   3: 4.239 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.363 ±(99.9%) 1.975 ms/op [Average]
  (min, avg, max) = (4.239, 4.363, 4.440), stdev = 0.108
  CI (99.9%): [2.388, 6.338] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.503 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.478 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.009 ms/op
Iteration   1: 4.160 ±(99.9%) 0.003 ms/op
Iteration   2: 4.052 ±(99.9%) 0.003 ms/op
Iteration   3: 4.092 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.101 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (4.052, 4.101, 4.160), stdev = 0.055
  CI (99.9%): [3.101, 5.102] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.753 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.760 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.507 ±(99.9%) 0.004 ms/op
Iteration   1: 4.481 ±(99.9%) 0.002 ms/op
Iteration   2: 4.424 ±(99.9%) 0.004 ms/op
Iteration   3: 4.392 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.433 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (4.392, 4.433, 4.481), stdev = 0.045
  CI (99.9%): [3.606, 5.259] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.614 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.983 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.686 ±(99.9%) 0.014 ms/op
Iteration   1: 5.566 ±(99.9%) 0.020 ms/op
Iteration   2: 5.559 ±(99.9%) 0.016 ms/op
Iteration   3: 5.793 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.639 ±(99.9%) 2.424 ms/op [Average]
  (min, avg, max) = (5.559, 5.639, 5.793), stdev = 0.133
  CI (99.9%): [3.215, 8.064] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.494 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.820 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.536 ±(99.9%) 0.014 ms/op
Iteration   1: 4.324 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  14.205 ms/op
                 createUser·p0.9999: 24.773 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   2: 4.461 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   7.234 ms/op
                 createUser·p0.999:  13.652 ms/op
                 createUser·p0.9999: 20.376 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   3: 4.347 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   5.751 ms/op
                 createUser·p0.99:   6.941 ms/op
                 createUser·p0.999:  13.016 ms/op
                 createUser·p0.9999: 29.491 ms/op
                 createUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219329
  mean =      4.377 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3919 
    [ 2.500,  5.000) = 178181 
    [ 5.000,  7.500) = 35501 
    [ 7.500, 10.000) = 1177 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     27.396 ms/op
     p(99.9990) =     30.048 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.299 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.011 ms/op
Iteration   1: 4.082 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   6.988 ms/op
                 existUser·p0.999:  11.846 ms/op
                 existUser·p0.9999: 15.128 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   2: 4.215 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.048 ms/op
                 existUser·p0.50:   4.145 ms/op
                 existUser·p0.90:   5.112 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  11.178 ms/op
                 existUser·p0.9999: 19.865 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   3: 3.903 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  12.142 ms/op
                 existUser·p0.9999: 22.243 ms/op
                 existUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236167
  mean =      4.063 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11398 
    [ 2.500,  5.000) = 198889 
    [ 5.000,  7.500) = 24568 
    [ 7.500, 10.000) = 801 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     23.099 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 6.831 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.481 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.300 ±(99.9%) 0.012 ms/op
Iteration   1: 4.318 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.562 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  11.729 ms/op
                 getUser·p0.9999: 17.865 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   2: 4.277 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  10.342 ms/op
                 getUser·p0.9999: 17.075 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   3: 4.387 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.399 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   7.824 ms/op
                 getUser·p0.999:  15.002 ms/op
                 getUser·p0.9999: 21.299 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221686
  mean =      4.327 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4858 
    [ 2.500,  5.000) = 182703 
    [ 5.000,  7.500) = 32120 
    [ 7.500, 10.000) = 1484 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     20.053 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 8.288 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 6.328 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.981 ±(99.9%) 0.025 ms/op
Iteration   1: 5.721 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   5.341 ms/op
                 listUser·p0.90:   7.881 ms/op
                 listUser·p0.95:   8.929 ms/op
                 listUser·p0.99:   11.291 ms/op
                 listUser·p0.999:  17.567 ms/op
                 listUser·p0.9999: 20.601 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   2: 5.795 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.774 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  19.491 ms/op
                 listUser·p0.9999: 26.229 ms/op
                 listUser·p1.00:   26.870 ms/op

Iteration   3: 5.610 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.372 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  24.442 ms/op
                 listUser·p0.9999: 30.981 ms/op
                 listUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168151
  mean =      5.708 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 101 
    [ 2.500,  5.000) = 56921 
    [ 5.000,  7.500) = 92728 
    [ 7.500, 10.000) = 15098 
    [10.000, 12.500) = 2542 
    [12.500, 15.000) = 396 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      7.643 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     19.394 ms/op
     p(99.9900) =     28.738 ms/op
     p(99.9990) =     31.358 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.246 ± 1.062  ops/ms
ClientGrpc.existUser                       thrpt       3   7.649 ± 0.391  ops/ms
ClientGrpc.getUser                         thrpt       3   7.239 ± 1.510  ops/ms
ClientGrpc.listUser                        thrpt       3   5.711 ± 2.380  ops/ms
ClientGrpc.createUser                       avgt       3   4.363 ± 1.975   ms/op
ClientGrpc.existUser                        avgt       3   4.101 ± 1.000   ms/op
ClientGrpc.getUser                          avgt       3   4.433 ± 0.826   ms/op
ClientGrpc.listUser                         avgt       3   5.639 ± 2.424   ms/op
ClientGrpc.createUser                     sample  219329   4.377 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.049           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.325           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.759           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.094           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.550           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.396           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.048           ms/op
ClientGrpc.existUser                      sample  236167   4.063 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.894           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.014           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.063           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.489           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.636           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.862           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.823           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.314           ms/op
ClientGrpc.getUser                        sample  221686   4.327 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.947           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.259           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.710           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.324           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.567           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.053           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  168151   5.708 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.382           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.382           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.643           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.667           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.977           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.394           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.738           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.425           ms/op
