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
# Warmup Iteration   1: 2.971 ops/ms
# Warmup Iteration   2: 6.567 ops/ms
# Warmup Iteration   3: 8.023 ops/ms
Iteration   1: 8.796 ops/ms
Iteration   2: 9.046 ops/ms
Iteration   3: 8.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.935 ±(99.9%) 2.319 ops/ms [Average]
  (min, avg, max) = (8.796, 8.935, 9.046), stdev = 0.127
  CI (99.9%): [6.616, 11.254] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.800 ops/ms
# Warmup Iteration   2: 8.393 ops/ms
# Warmup Iteration   3: 9.355 ops/ms
Iteration   1: 9.364 ops/ms
Iteration   2: 9.504 ops/ms
Iteration   3: 9.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.344 ±(99.9%) 3.133 ops/ms [Average]
  (min, avg, max) = (9.163, 9.344, 9.504), stdev = 0.172
  CI (99.9%): [6.211, 12.477] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.305 ops/ms
# Warmup Iteration   2: 8.375 ops/ms
# Warmup Iteration   3: 8.786 ops/ms
Iteration   1: 8.942 ops/ms
Iteration   2: 8.890 ops/ms
Iteration   3: 8.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.922 ±(99.9%) 0.511 ops/ms [Average]
  (min, avg, max) = (8.890, 8.922, 8.942), stdev = 0.028
  CI (99.9%): [8.411, 9.433] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.971 ops/ms
# Warmup Iteration   2: 6.598 ops/ms
# Warmup Iteration   3: 6.729 ops/ms
Iteration   1: 6.794 ops/ms
Iteration   2: 6.856 ops/ms
Iteration   3: 6.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.803 ±(99.9%) 0.883 ops/ms [Average]
  (min, avg, max) = (6.760, 6.803, 6.856), stdev = 0.048
  CI (99.9%): [5.920, 7.687] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.332 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.004 ms/op
Iteration   1: 3.598 ±(99.9%) 0.003 ms/op
Iteration   2: 3.582 ±(99.9%) 0.003 ms/op
Iteration   3: 3.604 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.595 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (3.582, 3.595, 3.604), stdev = 0.011
  CI (99.9%): [3.391, 3.798] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.004 ms/op
Iteration   1: 3.365 ±(99.9%) 0.003 ms/op
Iteration   2: 3.497 ±(99.9%) 0.005 ms/op
Iteration   3: 3.443 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.435 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (3.365, 3.435, 3.497), stdev = 0.067
  CI (99.9%): [2.222, 4.648] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.048 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.005 ms/op
Iteration   1: 3.625 ±(99.9%) 0.003 ms/op
Iteration   2: 3.621 ±(99.9%) 0.004 ms/op
Iteration   3: 3.614 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.620 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (3.614, 3.620, 3.625), stdev = 0.006
  CI (99.9%): [3.513, 3.727] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.103 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.872 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.714 ±(99.9%) 0.016 ms/op
Iteration   1: 4.599 ±(99.9%) 0.010 ms/op
Iteration   2: 4.669 ±(99.9%) 0.010 ms/op
Iteration   3: 4.606 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.625 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (4.599, 4.625, 4.669), stdev = 0.038
  CI (99.9%): [3.928, 5.322] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.059 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.008 ms/op
Iteration   1: 3.578 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  10.134 ms/op
                 createUser·p0.9999: 13.731 ms/op
                 createUser·p1.00:   15.532 ms/op

Iteration   2: 3.583 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  12.423 ms/op
                 createUser·p0.9999: 14.844 ms/op
                 createUser·p1.00:   15.532 ms/op

Iteration   3: 3.520 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   4.915 ms/op
                 createUser·p0.999:  10.649 ms/op
                 createUser·p0.9999: 18.022 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 269903
  mean =      3.560 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 6001 
    [ 2.500,  3.750) = 184846 
    [ 3.750,  5.000) = 74923 
    [ 5.000,  6.250) = 3010 
    [ 6.250,  7.500) = 425 
    [ 7.500,  8.750) = 180 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =     10.650 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.892 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.007 ms/op
Iteration   1: 3.453 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  8.978 ms/op
                 existUser·p0.9999: 14.188 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 3.286 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   4.923 ms/op
                 existUser·p0.999:  7.722 ms/op
                 existUser·p0.9999: 15.692 ms/op
                 existUser·p1.00:   16.105 ms/op

Iteration   3: 3.426 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  9.794 ms/op
                 existUser·p0.9999: 28.391 ms/op
                 existUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 283295
  mean =      3.387 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16826 
    [ 2.500,  5.000) = 263087 
    [ 5.000,  7.500) = 2803 
    [ 7.500, 10.000) = 356 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.145 ms/op
     p(99.9000) =      8.974 ms/op
     p(99.9900) =     26.237 ms/op
     p(99.9990) =     29.049 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.203 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.008 ms/op
Iteration   1: 3.622 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  11.993 ms/op
                 getUser·p0.9999: 17.373 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   2: 3.547 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  9.147 ms/op
                 getUser·p0.9999: 18.121 ms/op
                 getUser·p1.00:   19.726 ms/op

Iteration   3: 3.550 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 21.002 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268724
  mean =      3.573 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9072 
    [ 2.500,  5.000) = 253466 
    [ 5.000,  7.500) = 5434 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     10.830 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     21.516 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 6.150 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.854 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.692 ±(99.9%) 0.013 ms/op
Iteration   1: 4.655 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  14.986 ms/op
                 listUser·p0.9999: 17.699 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   2: 4.676 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  18.139 ms/op
                 listUser·p0.9999: 19.862 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   3: 4.536 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  18.440 ms/op
                 listUser·p0.9999: 32.111 ms/op
                 listUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207849
  mean =      4.621 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 175 
    [ 2.500,  5.000) = 170442 
    [ 5.000,  7.500) = 33202 
    [ 7.500, 10.000) = 3450 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.447 ms/op
     p(99.0000) =      8.102 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     31.347 ms/op
     p(99.9990) =     32.334 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.935 ± 2.319  ops/ms
ClientGrpc.existUser                       thrpt       3   9.344 ± 3.133  ops/ms
ClientGrpc.getUser                         thrpt       3   8.922 ± 0.511  ops/ms
ClientGrpc.listUser                        thrpt       3   6.803 ± 0.883  ops/ms
ClientGrpc.createUser                       avgt       3   3.595 ± 0.204   ms/op
ClientGrpc.existUser                        avgt       3   3.435 ± 1.213   ms/op
ClientGrpc.getUser                          avgt       3   3.620 ± 0.107   ms/op
ClientGrpc.listUser                         avgt       3   4.625 ± 0.697   ms/op
ClientGrpc.createUser                     sample  269903   3.560 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.745           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.174           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.650           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.105           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.645           ms/op
ClientGrpc.existUser                      sample  283295   3.387 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.878           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.002           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.974           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.237           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.131           ms/op
ClientGrpc.getUser                        sample  268724   3.573 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.866           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.830           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.268           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  207849   4.621 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.938           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.440           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.447           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.400           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.347           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.127           ms/op
