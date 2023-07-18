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
# Warmup Iteration   1: 5.033 ops/ms
# Warmup Iteration   2: 9.549 ops/ms
# Warmup Iteration   3: 10.436 ops/ms
Iteration   1: 10.618 ops/ms
Iteration   2: 10.677 ops/ms
Iteration   3: 10.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.635 ±(99.9%) 0.663 ops/ms [Average]
  (min, avg, max) = (10.611, 10.635, 10.677), stdev = 0.036
  CI (99.9%): [9.973, 11.298] (assumes normal distribution)


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
# Warmup Iteration   1: 7.546 ops/ms
# Warmup Iteration   2: 11.293 ops/ms
# Warmup Iteration   3: 11.294 ops/ms
Iteration   1: 11.258 ops/ms
Iteration   2: 11.273 ops/ms
Iteration   3: 11.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.260 ±(99.9%) 0.215 ops/ms [Average]
  (min, avg, max) = (11.250, 11.260, 11.273), stdev = 0.012
  CI (99.9%): [11.045, 11.476] (assumes normal distribution)


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
# Warmup Iteration   1: 7.695 ops/ms
# Warmup Iteration   2: 10.230 ops/ms
# Warmup Iteration   3: 10.950 ops/ms
Iteration   1: 10.792 ops/ms
Iteration   2: 10.673 ops/ms
Iteration   3: 10.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.724 ±(99.9%) 1.109 ops/ms [Average]
  (min, avg, max) = (10.673, 10.724, 10.792), stdev = 0.061
  CI (99.9%): [9.615, 11.834] (assumes normal distribution)


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
# Warmup Iteration   1: 6.394 ops/ms
# Warmup Iteration   2: 7.850 ops/ms
# Warmup Iteration   3: 8.227 ops/ms
Iteration   1: 8.238 ops/ms
Iteration   2: 8.361 ops/ms
Iteration   3: 8.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.324 ±(99.9%) 1.360 ops/ms [Average]
  (min, avg, max) = (8.238, 8.324, 8.373), stdev = 0.075
  CI (99.9%): [6.964, 9.684] (assumes normal distribution)


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.004 ms/op
Iteration   1: 3.002 ±(99.9%) 0.004 ms/op
Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
Iteration   3: 2.975 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.980 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (2.963, 2.980, 3.002), stdev = 0.020
  CI (99.9%): [2.621, 3.339] (assumes normal distribution)


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
# Warmup Iteration   1: 3.740 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.844 ±(99.9%) 0.003 ms/op
Iteration   1: 2.878 ±(99.9%) 0.004 ms/op
Iteration   2: 2.884 ±(99.9%) 0.004 ms/op
Iteration   3: 2.888 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.884 ±(99.9%) 0.090 ms/op [Average]
  (min, avg, max) = (2.878, 2.884, 2.888), stdev = 0.005
  CI (99.9%): [2.793, 2.974] (assumes normal distribution)


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
# Warmup Iteration   1: 3.939 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.004 ms/op
Iteration   1: 2.979 ±(99.9%) 0.002 ms/op
Iteration   2: 2.944 ±(99.9%) 0.004 ms/op
Iteration   3: 2.972 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.965 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (2.944, 2.965, 2.979), stdev = 0.019
  CI (99.9%): [2.625, 3.305] (assumes normal distribution)


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
# Warmup Iteration   1: 5.227 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.024 ms/op
Iteration   1: 3.916 ±(99.9%) 0.024 ms/op
Iteration   2: 3.876 ±(99.9%) 0.028 ms/op
Iteration   3: 3.885 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.893 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (3.876, 3.893, 3.916), stdev = 0.021
  CI (99.9%): [3.506, 4.279] (assumes normal distribution)


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  9.615 ms/op
                 createUser·p0.9999: 17.434 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   2: 2.973 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  6.843 ms/op
                 createUser·p0.9999: 21.561 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   3: 2.964 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.427 ms/op
                 createUser·p0.9999: 21.738 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323013
  mean =      2.973 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34397 
    [ 2.500,  5.000) = 287462 
    [ 5.000,  7.500) = 727 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.650 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     22.267 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.904 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.006 ms/op
Iteration   1: 2.861 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.101 ms/op
                 existUser·p0.999:  6.293 ms/op
                 existUser·p0.9999: 12.416 ms/op
                 existUser·p1.00:   12.747 ms/op

Iteration   2: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.456 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  7.081 ms/op
                 existUser·p0.9999: 24.244 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   3: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.342 ms/op
                 existUser·p0.9999: 15.443 ms/op
                 existUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334495
  mean =      2.870 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39815 
    [ 2.500,  5.000) = 293672 
    [ 5.000,  7.500) = 756 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      6.611 ms/op
     p(99.9900) =     22.646 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.007 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  6.071 ms/op
                 getUser·p0.9999: 17.387 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.502 ms/op
                 getUser·p0.9999: 23.690 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.516 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.634 ms/op
                 getUser·p0.9999: 16.856 ms/op
                 getUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320028
  mean =      2.999 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22980 
    [ 2.500,  5.000) = 296073 
    [ 5.000,  7.500) = 648 
    [ 7.500, 10.000) = 131 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.290 ms/op
     p(99.9000) =      7.626 ms/op
     p(99.9900) =     21.424 ms/op
     p(99.9990) =     23.914 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.010 ms/op
Iteration   1: 3.919 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.737 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  12.272 ms/op
                 listUser·p0.9999: 14.147 ms/op
                 listUser·p1.00:   15.614 ms/op

Iteration   2: 3.816 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 16.797 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   3: 3.898 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.287 ms/op
                 listUser·p0.9999: 16.757 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247496
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 5804 
    [ 2.500,  3.750) = 118452 
    [ 3.750,  5.000) = 101881 
    [ 5.000,  6.250) = 16063 
    [ 6.250,  7.500) = 4011 
    [ 7.500,  8.750) = 549 
    [ 8.750, 10.000) = 181 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 149 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 79 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     16.228 ms/op
     p(99.9990) =     18.244 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.635 ± 0.663  ops/ms
ClientGrpc.existUser                       thrpt       3  11.260 ± 0.215  ops/ms
ClientGrpc.getUser                         thrpt       3  10.724 ± 1.109  ops/ms
ClientGrpc.listUser                        thrpt       3   8.324 ± 1.360  ops/ms
ClientGrpc.createUser                       avgt       3   2.980 ± 0.359   ms/op
ClientGrpc.existUser                        avgt       3   2.884 ± 0.090   ms/op
ClientGrpc.getUser                          avgt       3   2.965 ± 0.340   ms/op
ClientGrpc.listUser                         avgt       3   3.893 ± 0.386   ms/op
ClientGrpc.createUser                     sample  323013   2.973 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.660           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.650           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.463           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.348           ms/op
ClientGrpc.existUser                      sample  334495   2.870 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.456           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.611           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.646           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.543           ms/op
ClientGrpc.getUser                        sample  320028   2.999 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.516           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.290           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.626           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.424           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.953           ms/op
ClientGrpc.listUser                       sample  247496   3.877 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.737           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.140           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.228           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.137           ms/op
