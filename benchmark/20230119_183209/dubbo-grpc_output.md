# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.695 ops/ms
# Warmup Iteration   2: 7.334 ops/ms
# Warmup Iteration   3: 8.801 ops/ms
Iteration   1: 8.553 ops/ms
Iteration   2: 8.813 ops/ms
Iteration   3: 8.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.786 ±(99.9%) 4.044 ops/ms [Average]
  (min, avg, max) = (8.553, 8.786, 8.994), stdev = 0.222
  CI (99.9%): [4.742, 12.831] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.238 ops/ms
# Warmup Iteration   2: 8.695 ops/ms
# Warmup Iteration   3: 9.265 ops/ms
Iteration   1: 9.279 ops/ms
Iteration   2: 9.159 ops/ms
Iteration   3: 9.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.256 ±(99.9%) 1.601 ops/ms [Average]
  (min, avg, max) = (9.159, 9.256, 9.330), stdev = 0.088
  CI (99.9%): [7.654, 10.857] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.860 ops/ms
# Warmup Iteration   2: 8.169 ops/ms
# Warmup Iteration   3: 8.279 ops/ms
Iteration   1: 8.677 ops/ms
Iteration   2: 8.864 ops/ms
Iteration   3: 8.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.694 ±(99.9%) 2.967 ops/ms [Average]
  (min, avg, max) = (8.540, 8.694, 8.864), stdev = 0.163
  CI (99.9%): [5.727, 11.661] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.136 ops/ms
# Warmup Iteration   2: 6.245 ops/ms
# Warmup Iteration   3: 6.780 ops/ms
Iteration   1: 6.852 ops/ms
Iteration   2: 6.930 ops/ms
Iteration   3: 6.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.900 ±(99.9%) 0.764 ops/ms [Average]
  (min, avg, max) = (6.852, 6.900, 6.930), stdev = 0.042
  CI (99.9%): [6.135, 7.664] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.208 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.736 ±(99.9%) 0.003 ms/op
Iteration   1: 3.682 ±(99.9%) 0.004 ms/op
Iteration   2: 3.649 ±(99.9%) 0.004 ms/op
Iteration   3: 3.694 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.675 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.649, 3.675, 3.694), stdev = 0.023
  CI (99.9%): [3.252, 4.098] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.786 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.004 ms/op
Iteration   1: 3.545 ±(99.9%) 0.003 ms/op
Iteration   2: 3.462 ±(99.9%) 0.003 ms/op
Iteration   3: 3.483 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.497 ±(99.9%) 0.790 ms/op [Average]
  (min, avg, max) = (3.462, 3.497, 3.545), stdev = 0.043
  CI (99.9%): [2.706, 4.287] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.084 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.657 ±(99.9%) 0.004 ms/op
Iteration   1: 3.676 ±(99.9%) 0.003 ms/op
Iteration   2: 3.607 ±(99.9%) 0.003 ms/op
Iteration   3: 3.628 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.637 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.607, 3.637, 3.676), stdev = 0.036
  CI (99.9%): [2.987, 4.286] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.456 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.622 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.604 ±(99.9%) 0.017 ms/op
Iteration   1: 4.413 ±(99.9%) 0.035 ms/op
Iteration   2: 4.563 ±(99.9%) 0.018 ms/op
Iteration   3: 4.566 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.514 ±(99.9%) 1.591 ms/op [Average]
  (min, avg, max) = (4.413, 4.514, 4.566), stdev = 0.087
  CI (99.9%): [2.923, 6.105] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.995 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.702 ±(99.9%) 0.008 ms/op
Iteration   1: 3.586 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  7.854 ms/op
                 createUser·p0.9999: 14.240 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 3.631 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  9.689 ms/op
                 createUser·p0.9999: 18.907 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   3: 3.716 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   5.166 ms/op
                 createUser·p0.999:  7.616 ms/op
                 createUser·p0.9999: 20.329 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263557
  mean =      3.643 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10800 
    [ 2.500,  5.000) = 248111 
    [ 5.000,  7.500) = 4265 
    [ 7.500, 10.000) = 172 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =      8.196 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.853 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.008 ms/op
Iteration   1: 3.607 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  6.380 ms/op
                 existUser·p0.9999: 19.927 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   2: 3.542 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   4.981 ms/op
                 existUser·p0.999:  8.328 ms/op
                 existUser·p0.9999: 15.531 ms/op
                 existUser·p1.00:   15.958 ms/op

Iteration   3: 3.557 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  8.456 ms/op
                 existUser·p0.9999: 34.276 ms/op
                 existUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268882
  mean =      3.568 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13953 
    [ 2.500,  5.000) = 251419 
    [ 5.000,  7.500) = 3189 
    [ 7.500, 10.000) = 189 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.104 ms/op
     p(99.9000) =      7.925 ms/op
     p(99.9900) =     33.190 ms/op
     p(99.9990) =     34.537 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.406 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.008 ms/op
Iteration   1: 3.702 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  8.425 ms/op
                 getUser·p0.9999: 18.350 ms/op
                 getUser·p1.00:   18.645 ms/op

Iteration   2: 3.692 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  8.393 ms/op
                 getUser·p0.9999: 27.809 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 3.763 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  9.634 ms/op
                 getUser·p0.9999: 17.383 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258100
  mean =      3.719 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8072 
    [ 2.500,  5.000) = 244107 
    [ 5.000,  7.500) = 5398 
    [ 7.500, 10.000) = 348 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     26.981 ms/op
     p(99.9990) =     28.239 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.520 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.808 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.624 ±(99.9%) 0.012 ms/op
Iteration   1: 4.660 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   6.341 ms/op
                 listUser·p0.99:   7.945 ms/op
                 listUser·p0.999:  15.489 ms/op
                 listUser·p0.9999: 19.113 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   2: 4.668 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.537 ms/op
                 listUser·p0.99:   7.986 ms/op
                 listUser·p0.999:  15.335 ms/op
                 listUser·p0.9999: 19.240 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 4.600 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.751 ms/op
                 listUser·p0.95:   6.586 ms/op
                 listUser·p0.99:   8.208 ms/op
                 listUser·p0.999:  19.890 ms/op
                 listUser·p0.9999: 26.214 ms/op
                 listUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206634
  mean =      4.643 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 365 
    [ 2.500,  5.000) = 165839 
    [ 5.000,  7.500) = 36659 
    [ 7.500, 10.000) = 3263 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.767 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     16.158 ms/op
     p(99.9900) =     25.549 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.786 ± 4.044  ops/ms
ClientGrpc.existUser                       thrpt       3   9.256 ± 1.601  ops/ms
ClientGrpc.getUser                         thrpt       3   8.694 ± 2.967  ops/ms
ClientGrpc.listUser                        thrpt       3   6.900 ± 0.764  ops/ms
ClientGrpc.createUser                       avgt       3   3.675 ± 0.423   ms/op
ClientGrpc.existUser                        avgt       3   3.497 ± 0.790   ms/op
ClientGrpc.getUser                          avgt       3   3.637 ± 0.649   ms/op
ClientGrpc.listUser                         avgt       3   4.514 ± 1.591   ms/op
ClientGrpc.createUser                     sample  263557   3.643 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.723           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.177           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.196           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.431           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.709           ms/op
ClientGrpc.existUser                      sample  268882   3.568 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.904           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.925           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.190           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.603           ms/op
ClientGrpc.getUser                        sample  258100   3.719 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.652           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.382           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.782           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.981           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.229           ms/op
ClientGrpc.listUser                       sample  206634   4.643 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.333           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.473           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.496           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.158           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.549           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.411           ms/op
