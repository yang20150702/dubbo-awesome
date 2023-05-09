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
# Warmup Iteration   1: 4.141 ops/ms
# Warmup Iteration   2: 9.261 ops/ms
# Warmup Iteration   3: 10.218 ops/ms
Iteration   1: 10.244 ops/ms
Iteration   2: 10.449 ops/ms
Iteration   3: 10.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.373 ±(99.9%) 2.053 ops/ms [Average]
  (min, avg, max) = (10.244, 10.373, 10.449), stdev = 0.113
  CI (99.9%): [8.320, 12.426] (assumes normal distribution)


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
# Warmup Iteration   1: 7.439 ops/ms
# Warmup Iteration   2: 10.718 ops/ms
# Warmup Iteration   3: 11.328 ops/ms
Iteration   1: 10.864 ops/ms
Iteration   2: 11.357 ops/ms
Iteration   3: 11.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.202 ±(99.9%) 5.345 ops/ms [Average]
  (min, avg, max) = (10.864, 11.202, 11.384), stdev = 0.293
  CI (99.9%): [5.857, 16.546] (assumes normal distribution)


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
# Warmup Iteration   1: 6.413 ops/ms
# Warmup Iteration   2: 10.122 ops/ms
# Warmup Iteration   3: 10.371 ops/ms
Iteration   1: 10.480 ops/ms
Iteration   2: 10.498 ops/ms
Iteration   3: 10.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.470 ±(99.9%) 0.614 ops/ms [Average]
  (min, avg, max) = (10.433, 10.470, 10.498), stdev = 0.034
  CI (99.9%): [9.857, 11.084] (assumes normal distribution)


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
# Warmup Iteration   1: 5.611 ops/ms
# Warmup Iteration   2: 7.521 ops/ms
# Warmup Iteration   3: 7.822 ops/ms
Iteration   1: 7.889 ops/ms
Iteration   2: 7.909 ops/ms
Iteration   3: 7.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.927 ±(99.9%) 0.914 ops/ms [Average]
  (min, avg, max) = (7.889, 7.927, 7.984), stdev = 0.050
  CI (99.9%): [7.013, 8.841] (assumes normal distribution)


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
# Warmup Iteration   1: 4.443 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.003 ms/op
Iteration   1: 2.999 ±(99.9%) 0.003 ms/op
Iteration   2: 3.064 ±(99.9%) 0.003 ms/op
Iteration   3: 3.053 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.039 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (2.999, 3.039, 3.064), stdev = 0.035
  CI (99.9%): [2.405, 3.673] (assumes normal distribution)


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.002 ms/op
Iteration   1: 2.950 ±(99.9%) 0.002 ms/op
Iteration   2: 2.961 ±(99.9%) 0.001 ms/op
Iteration   3: 2.864 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.925 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (2.864, 2.925, 2.961), stdev = 0.053
  CI (99.9%): [1.957, 3.893] (assumes normal distribution)


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.003 ms/op
Iteration   1: 3.012 ±(99.9%) 0.003 ms/op
Iteration   2: 3.039 ±(99.9%) 0.004 ms/op
Iteration   3: 3.028 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.026 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (3.012, 3.026, 3.039), stdev = 0.013
  CI (99.9%): [2.786, 3.267] (assumes normal distribution)


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
# Warmup Iteration   1: 6.024 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.008 ms/op
Iteration   1: 4.043 ±(99.9%) 0.017 ms/op
Iteration   2: 3.904 ±(99.9%) 0.009 ms/op
Iteration   3: 3.953 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.967 ±(99.9%) 1.287 ms/op [Average]
  (min, avg, max) = (3.904, 3.967, 4.043), stdev = 0.071
  CI (99.9%): [2.679, 5.254] (assumes normal distribution)


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
# Warmup Iteration   1: 4.440 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.900 ms/op
                 createUser·p0.9999: 16.958 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.721 ms/op
                 createUser·p0.9999: 12.894 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  10.584 ms/op
                 createUser·p0.9999: 17.924 ms/op
                 createUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315518
  mean =      3.041 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 503 
    [ 1.250,  2.500) = 18059 
    [ 2.500,  3.750) = 282788 
    [ 3.750,  5.000) = 12804 
    [ 5.000,  6.250) = 677 
    [ 6.250,  7.500) = 251 
    [ 7.500,  8.750) = 123 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     17.054 ms/op
     p(99.9990) =     18.138 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.005 ms/op
Iteration   1: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   3.957 ms/op
                 existUser·p0.999:  6.432 ms/op
                 existUser·p0.9999: 12.133 ms/op
                 existUser·p1.00:   12.714 ms/op

Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  7.111 ms/op
                 existUser·p0.9999: 21.889 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   3: 2.903 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.359 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.951 ms/op
                 existUser·p0.9999: 16.216 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327405
  mean =      2.935 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30884 
    [ 2.500,  5.000) = 295462 
    [ 5.000,  7.500) = 815 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =      6.744 ms/op
     p(99.9900) =     20.521 ms/op
     p(99.9990) =     22.077 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  8.368 ms/op
                 getUser·p0.9999: 14.586 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   2: 3.029 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  7.655 ms/op
                 getUser·p0.9999: 26.950 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.021 ms/op
                 getUser·p0.9999: 18.055 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314780
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19137 
    [ 2.500,  5.000) = 293826 
    [ 5.000,  7.500) = 1486 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.676 ms/op
     p(99.9900) =     26.298 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 5.682 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.312 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.011 ms/op
Iteration   1: 4.030 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 17.303 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  14.277 ms/op
                 listUser·p0.9999: 22.319 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   3: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.959 ms/op
                 listUser·p0.999:  16.384 ms/op
                 listUser·p0.9999: 27.191 ms/op
                 listUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239275
  mean =      4.011 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3178 
    [ 2.500,  5.000) = 213318 
    [ 5.000,  7.500) = 21319 
    [ 7.500, 10.000) = 1009 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.486 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.373 ± 2.053  ops/ms
ClientGrpc.existUser                       thrpt       3  11.202 ± 5.345  ops/ms
ClientGrpc.getUser                         thrpt       3  10.470 ± 0.614  ops/ms
ClientGrpc.listUser                        thrpt       3   7.927 ± 0.914  ops/ms
ClientGrpc.createUser                       avgt       3   3.039 ± 0.634   ms/op
ClientGrpc.existUser                        avgt       3   2.925 ± 0.968   ms/op
ClientGrpc.getUser                          avgt       3   3.026 ± 0.240   ms/op
ClientGrpc.listUser                         avgt       3   3.967 ± 1.287   ms/op
ClientGrpc.createUser                     sample  315518   3.041 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.702           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.716           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.054           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.153           ms/op
ClientGrpc.existUser                      sample  327405   2.935 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.640           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.744           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.521           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.151           ms/op
ClientGrpc.getUser                        sample  314780   3.047 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.760           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.676           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.298           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.197           ms/op
ClientGrpc.listUser                       sample  239275   4.011 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.844           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.486           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.413           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.082           ms/op
