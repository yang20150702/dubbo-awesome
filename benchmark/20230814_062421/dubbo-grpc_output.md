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
# Warmup Iteration   1: 2.482 ops/ms
# Warmup Iteration   2: 5.817 ops/ms
# Warmup Iteration   3: 7.046 ops/ms
Iteration   1: 7.224 ops/ms
Iteration   2: 7.260 ops/ms
Iteration   3: 7.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.359 ±(99.9%) 3.701 ops/ms [Average]
  (min, avg, max) = (7.224, 7.359, 7.592), stdev = 0.203
  CI (99.9%): [3.658, 11.060] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.895 ops/ms
# Warmup Iteration   2: 7.246 ops/ms
# Warmup Iteration   3: 8.140 ops/ms
Iteration   1: 8.239 ops/ms
Iteration   2: 8.205 ops/ms
Iteration   3: 8.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.280 ±(99.9%) 1.855 ops/ms [Average]
  (min, avg, max) = (8.205, 8.280, 8.396), stdev = 0.102
  CI (99.9%): [6.425, 10.135] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.635 ops/ms
# Warmup Iteration   2: 6.999 ops/ms
# Warmup Iteration   3: 7.716 ops/ms
Iteration   1: 7.247 ops/ms
Iteration   2: 7.256 ops/ms
Iteration   3: 7.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.430 ±(99.9%) 5.624 ops/ms [Average]
  (min, avg, max) = (7.247, 7.430, 7.786), stdev = 0.308
  CI (99.9%): [1.806, 13.054] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.666 ops/ms
# Warmup Iteration   2: 5.403 ops/ms
# Warmup Iteration   3: 5.801 ops/ms
Iteration   1: 6.147 ops/ms
Iteration   2: 6.029 ops/ms
Iteration   3: 5.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.040 ±(99.9%) 1.863 ops/ms [Average]
  (min, avg, max) = (5.943, 6.040, 6.147), stdev = 0.102
  CI (99.9%): [4.177, 7.902] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.447 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.005 ms/op
Iteration   1: 3.938 ±(99.9%) 0.003 ms/op
Iteration   2: 4.009 ±(99.9%) 0.003 ms/op
Iteration   3: 4.295 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.081 ±(99.9%) 3.448 ms/op [Average]
  (min, avg, max) = (3.938, 4.081, 4.295), stdev = 0.189
  CI (99.9%): [0.632, 7.529] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.862 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.242 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.004 ms/op
Iteration   1: 4.174 ±(99.9%) 0.004 ms/op
Iteration   2: 4.182 ±(99.9%) 0.003 ms/op
Iteration   3: 3.975 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.111 ±(99.9%) 2.142 ms/op [Average]
  (min, avg, max) = (3.975, 4.111, 4.182), stdev = 0.117
  CI (99.9%): [1.969, 6.253] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.614 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.450 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.010 ms/op
Iteration   1: 4.459 ±(99.9%) 0.003 ms/op
Iteration   2: 4.573 ±(99.9%) 0.005 ms/op
Iteration   3: 4.321 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.451 ±(99.9%) 2.301 ms/op [Average]
  (min, avg, max) = (4.321, 4.451, 4.573), stdev = 0.126
  CI (99.9%): [2.150, 6.753] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.942 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.679 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.445 ±(99.9%) 0.012 ms/op
Iteration   1: 5.684 ±(99.9%) 0.020 ms/op
Iteration   2: 5.740 ±(99.9%) 0.028 ms/op
Iteration   3: 5.506 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.643 ±(99.9%) 2.229 ms/op [Average]
  (min, avg, max) = (5.506, 5.643, 5.740), stdev = 0.122
  CI (99.9%): [3.414, 7.872] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.369 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.577 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.370 ±(99.9%) 0.015 ms/op
Iteration   1: 4.341 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.401 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.464 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  10.916 ms/op
                 createUser·p0.9999: 16.800 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 4.181 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  11.256 ms/op
                 createUser·p0.9999: 24.697 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 4.134 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  10.207 ms/op
                 createUser·p0.9999: 19.957 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227643
  mean =      4.217 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4651 
    [ 2.500,  5.000) = 182797 
    [ 5.000,  7.500) = 38269 
    [ 7.500, 10.000) = 1552 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     10.813 ms/op
     p(99.9900) =     23.788 ms/op
     p(99.9990) =     25.237 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 6.139 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.012 ms/op
Iteration   1: 4.171 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   4.026 ms/op
                 existUser·p0.90:   5.382 ms/op
                 existUser·p0.95:   5.849 ms/op
                 existUser·p0.99:   7.245 ms/op
                 existUser·p0.999:  11.059 ms/op
                 existUser·p0.9999: 16.122 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   2: 4.125 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   3.981 ms/op
                 existUser·p0.90:   5.317 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   7.283 ms/op
                 existUser·p0.999:  11.616 ms/op
                 existUser·p0.9999: 18.252 ms/op
                 existUser·p1.00:   18.514 ms/op

Iteration   3: 4.120 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   3.985 ms/op
                 existUser·p0.90:   5.325 ms/op
                 existUser·p0.95:   5.816 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  12.059 ms/op
                 existUser·p0.9999: 20.709 ms/op
                 existUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 231773
  mean =      4.139 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4395 
    [ 2.500,  5.000) = 190407 
    [ 5.000,  7.500) = 34956 
    [ 7.500, 10.000) = 1534 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     20.206 ms/op
     p(99.9990) =     23.599 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.660 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.692 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.416 ±(99.9%) 0.014 ms/op
Iteration   1: 4.128 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   5.852 ms/op
                 getUser·p0.99:   7.561 ms/op
                 getUser·p0.999:  10.093 ms/op
                 getUser·p0.9999: 13.701 ms/op
                 getUser·p1.00:   16.663 ms/op

Iteration   2: 4.390 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   7.537 ms/op
                 getUser·p0.999:  11.912 ms/op
                 getUser·p0.9999: 17.118 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   3: 4.235 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   4.104 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   5.874 ms/op
                 getUser·p0.99:   7.747 ms/op
                 getUser·p0.999:  12.665 ms/op
                 getUser·p0.9999: 19.741 ms/op
                 getUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 225955
  mean =      4.249 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4929 
    [ 2.500,  5.000) = 179187 
    [ 5.000,  7.500) = 39411 
    [ 7.500, 10.000) = 1937 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      7.598 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     19.321 ms/op
     p(99.9990) =     20.829 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.521 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.258 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.531 ±(99.9%) 0.021 ms/op
Iteration   1: 5.428 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   7.037 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   10.093 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 19.206 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   2: 5.545 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   5.259 ms/op
                 listUser·p0.90:   7.266 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  18.917 ms/op
                 listUser·p0.9999: 20.954 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   3: 5.353 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.595 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  18.596 ms/op
                 listUser·p0.9999: 29.033 ms/op
                 listUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176378
  mean =      5.441 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 217 
    [ 2.500,  5.000) = 75346 
    [ 5.000,  7.500) = 87423 
    [ 7.500, 10.000) = 11089 
    [10.000, 12.500) = 1740 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.094 ms/op
     p(95.0000) =      8.167 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     28.618 ms/op
     p(99.9990) =     30.382 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.359 ± 3.701  ops/ms
ClientGrpc.existUser                       thrpt       3   8.280 ± 1.855  ops/ms
ClientGrpc.getUser                         thrpt       3   7.430 ± 5.624  ops/ms
ClientGrpc.listUser                        thrpt       3   6.040 ± 1.863  ops/ms
ClientGrpc.createUser                       avgt       3   4.081 ± 3.448   ms/op
ClientGrpc.existUser                        avgt       3   4.111 ± 2.142   ms/op
ClientGrpc.getUser                          avgt       3   4.451 ± 2.301   ms/op
ClientGrpc.listUser                         avgt       3   5.643 ± 2.229   ms/op
ClientGrpc.createUser                     sample  227643   4.217 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.811           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.104           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.390           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.299           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.813           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.788           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.362           ms/op
ClientGrpc.existUser                      sample  231773   4.139 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.925           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.341           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.816           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.340           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.436           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.206           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.724           ms/op
ClientGrpc.getUser                        sample  225955   4.249 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.950           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.448           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.947           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.598           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.567           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.321           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.856           ms/op
ClientGrpc.listUser                       sample  176378   5.441 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.272           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.167           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.387           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.400           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.618           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.507           ms/op
