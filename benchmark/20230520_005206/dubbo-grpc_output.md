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
# Warmup Iteration   1: 2.284 ops/ms
# Warmup Iteration   2: 5.577 ops/ms
# Warmup Iteration   3: 7.067 ops/ms
Iteration   1: 7.554 ops/ms
Iteration   2: 7.646 ops/ms
Iteration   3: 7.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.559 ±(99.9%) 1.548 ops/ms [Average]
  (min, avg, max) = (7.476, 7.559, 7.646), stdev = 0.085
  CI (99.9%): [6.010, 9.107] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.687 ops/ms
# Warmup Iteration   2: 7.256 ops/ms
# Warmup Iteration   3: 7.598 ops/ms
Iteration   1: 8.007 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 8.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.060 ±(99.9%) 0.831 ops/ms [Average]
  (min, avg, max) = (8.007, 8.060, 8.086), stdev = 0.046
  CI (99.9%): [7.228, 8.891] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.447 ops/ms
# Warmup Iteration   2: 7.020 ops/ms
# Warmup Iteration   3: 7.403 ops/ms
Iteration   1: 7.917 ops/ms
Iteration   2: 7.702 ops/ms
Iteration   3: 7.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.798 ±(99.9%) 1.998 ops/ms [Average]
  (min, avg, max) = (7.702, 7.798, 7.917), stdev = 0.110
  CI (99.9%): [5.800, 9.796] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.578 ops/ms
# Warmup Iteration   2: 5.037 ops/ms
# Warmup Iteration   3: 5.625 ops/ms
Iteration   1: 6.012 ops/ms
Iteration   2: 5.752 ops/ms
Iteration   3: 5.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.850 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (5.752, 5.850, 6.012), stdev = 0.142
  CI (99.9%): [3.268, 8.432] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.730 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.384 ±(99.9%) 0.002 ms/op
Iteration   1: 4.295 ±(99.9%) 0.003 ms/op
Iteration   2: 4.172 ±(99.9%) 0.003 ms/op
Iteration   3: 4.214 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.227 ±(99.9%) 1.139 ms/op [Average]
  (min, avg, max) = (4.172, 4.227, 4.295), stdev = 0.062
  CI (99.9%): [3.088, 5.366] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.049 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.002 ms/op
Iteration   1: 4.068 ±(99.9%) 0.002 ms/op
Iteration   2: 3.978 ±(99.9%) 0.002 ms/op
Iteration   3: 3.944 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.996 ±(99.9%) 1.168 ms/op [Average]
  (min, avg, max) = (3.944, 3.996, 4.068), stdev = 0.064
  CI (99.9%): [2.829, 5.164] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.626 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.481 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.004 ms/op
Iteration   1: 4.306 ±(99.9%) 0.004 ms/op
Iteration   2: 4.393 ±(99.9%) 0.004 ms/op
Iteration   3: 4.227 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.309 ±(99.9%) 1.521 ms/op [Average]
  (min, avg, max) = (4.227, 4.309, 4.393), stdev = 0.083
  CI (99.9%): [2.788, 5.830] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.213 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.230 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.656 ±(99.9%) 0.023 ms/op
Iteration   1: 5.568 ±(99.9%) 0.014 ms/op
Iteration   2: 5.689 ±(99.9%) 0.013 ms/op
Iteration   3: 5.725 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.661 ±(99.9%) 1.502 ms/op [Average]
  (min, avg, max) = (5.568, 5.661, 5.725), stdev = 0.082
  CI (99.9%): [4.159, 7.163] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.090 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.012 ms/op
Iteration   1: 4.128 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   4.047 ms/op
                 createUser·p0.90:   5.153 ms/op
                 createUser·p0.95:   5.726 ms/op
                 createUser·p0.99:   7.651 ms/op
                 createUser·p0.999:  12.482 ms/op
                 createUser·p0.9999: 15.196 ms/op
                 createUser·p1.00:   15.532 ms/op

Iteration   2: 4.208 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   4.108 ms/op
                 createUser·p0.90:   5.186 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  13.890 ms/op
                 createUser·p0.9999: 30.409 ms/op
                 createUser·p1.00:   30.802 ms/op

Iteration   3: 4.169 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   4.100 ms/op
                 createUser·p0.90:   5.153 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  10.795 ms/op
                 createUser·p0.9999: 37.159 ms/op
                 createUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 230333
  mean =      4.168 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7452 
    [ 2.500,  5.000) = 193507 
    [ 5.000,  7.500) = 27576 
    [ 7.500, 10.000) = 1156 
    [10.000, 12.500) = 436 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     12.206 ms/op
     p(99.9900) =     34.732 ms/op
     p(99.9990) =     37.401 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.856 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.012 ms/op
Iteration   1: 3.895 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   6.921 ms/op
                 existUser·p0.999:  12.190 ms/op
                 existUser·p0.9999: 17.098 ms/op
                 existUser·p1.00:   18.776 ms/op

Iteration   2: 3.916 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  8.867 ms/op
                 existUser·p0.9999: 29.119 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   3: 3.863 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  9.063 ms/op
                 existUser·p0.9999: 24.745 ms/op
                 existUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 246741
  mean =      3.891 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3676 
    [ 2.500,  5.000) = 227362 
    [ 5.000,  7.500) = 14437 
    [ 7.500, 10.000) = 1049 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     28.180 ms/op
     p(99.9990) =     29.395 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.453 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.446 ±(99.9%) 0.013 ms/op
Iteration   1: 4.362 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  12.114 ms/op
                 getUser·p0.9999: 15.898 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   2: 4.480 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  10.410 ms/op
                 getUser·p0.9999: 19.516 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   3: 4.325 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  10.389 ms/op
                 getUser·p0.9999: 23.023 ms/op
                 getUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218692
  mean =      4.388 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3623 
    [ 2.500,  5.000) = 170265 
    [ 5.000,  7.500) = 42805 
    [ 7.500, 10.000) = 1657 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     11.212 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     23.444 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.892 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 6.116 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.499 ±(99.9%) 0.022 ms/op
Iteration   1: 5.524 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   7.365 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   10.551 ms/op
                 listUser·p0.999:  17.167 ms/op
                 listUser·p0.9999: 24.359 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   2: 5.775 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   7.807 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   10.764 ms/op
                 listUser·p0.999:  22.844 ms/op
                 listUser·p0.9999: 29.503 ms/op
                 listUser·p1.00:   29.917 ms/op

Iteration   3: 5.615 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   5.251 ms/op
                 listUser·p0.90:   7.524 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   10.790 ms/op
                 listUser·p0.999:  23.365 ms/op
                 listUser·p0.9999: 32.700 ms/op
                 listUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 170394
  mean =      5.636 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 123 
    [ 2.500,  5.000) = 63853 
    [ 5.000,  7.500) = 88371 
    [ 7.500, 10.000) = 15199 
    [10.000, 12.500) = 2138 
    [12.500, 15.000) = 360 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      7.586 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     21.660 ms/op
     p(99.9900) =     30.507 ms/op
     p(99.9990) =     33.050 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.559 ± 1.548  ops/ms
ClientGrpc.existUser                       thrpt       3   8.060 ± 0.831  ops/ms
ClientGrpc.getUser                         thrpt       3   7.798 ± 1.998  ops/ms
ClientGrpc.listUser                        thrpt       3   5.850 ± 2.582  ops/ms
ClientGrpc.createUser                       avgt       3   4.227 ± 1.139   ms/op
ClientGrpc.existUser                        avgt       3   3.996 ± 1.168   ms/op
ClientGrpc.getUser                          avgt       3   4.309 ± 1.521   ms/op
ClientGrpc.listUser                         avgt       3   5.661 ± 1.502   ms/op
ClientGrpc.createUser                     sample  230333   4.168 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.892           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.169           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.661           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.094           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.206           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.732           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          37.421           ms/op
ClientGrpc.existUser                      sample  246741   3.891 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.887           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.751           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.136           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.431           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.486           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.180           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.426           ms/op
ClientGrpc.getUser                        sample  218692   4.388 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.094           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.505           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.947           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.381           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.212           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.496           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.462           ms/op
ClientGrpc.listUser                       sample  170394   5.636 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.196           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.586           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.602           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.715           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.660           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.507           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.096           ms/op
