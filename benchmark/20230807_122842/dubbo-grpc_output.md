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
# Warmup Iteration   1: 4.069 ops/ms
# Warmup Iteration   2: 8.607 ops/ms
# Warmup Iteration   3: 9.983 ops/ms
Iteration   1: 10.375 ops/ms
Iteration   2: 10.304 ops/ms
Iteration   3: 10.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.395 ±(99.9%) 1.856 ops/ms [Average]
  (min, avg, max) = (10.304, 10.395, 10.505), stdev = 0.102
  CI (99.9%): [8.538, 12.251] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.964 ops/ms
# Warmup Iteration   2: 10.434 ops/ms
# Warmup Iteration   3: 10.976 ops/ms
Iteration   1: 10.613 ops/ms
Iteration   2: 10.954 ops/ms
Iteration   3: 10.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.812 ±(99.9%) 3.239 ops/ms [Average]
  (min, avg, max) = (10.613, 10.812, 10.954), stdev = 0.178
  CI (99.9%): [7.574, 14.051] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.825 ops/ms
# Warmup Iteration   2: 9.821 ops/ms
# Warmup Iteration   3: 10.204 ops/ms
Iteration   1: 10.263 ops/ms
Iteration   2: 10.394 ops/ms
Iteration   3: 10.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.296 ±(99.9%) 1.584 ops/ms [Average]
  (min, avg, max) = (10.230, 10.296, 10.394), stdev = 0.087
  CI (99.9%): [8.712, 11.880] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.585 ops/ms
# Warmup Iteration   2: 7.466 ops/ms
# Warmup Iteration   3: 7.920 ops/ms
Iteration   1: 7.769 ops/ms
Iteration   2: 8.010 ops/ms
Iteration   3: 7.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.879 ±(99.9%) 2.213 ops/ms [Average]
  (min, avg, max) = (7.769, 7.879, 8.010), stdev = 0.121
  CI (99.9%): [5.667, 10.092] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.367 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.004 ms/op
Iteration   1: 3.126 ±(99.9%) 0.008 ms/op
Iteration   2: 3.081 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.103 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (3.081, 3.103, 3.126), stdev = 0.022
  CI (99.9%): [2.696, 3.509] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.003 ms/op
Iteration   1: 2.976 ±(99.9%) 0.003 ms/op
Iteration   2: 2.900 ±(99.9%) 0.002 ms/op
Iteration   3: 2.864 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.913 ±(99.9%) 1.044 ms/op [Average]
  (min, avg, max) = (2.864, 2.913, 2.976), stdev = 0.057
  CI (99.9%): [1.869, 3.958] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.070 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.004 ms/op
Iteration   1: 3.062 ±(99.9%) 0.003 ms/op
Iteration   2: 3.081 ±(99.9%) 0.004 ms/op
Iteration   3: 3.067 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.070 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (3.062, 3.070, 3.081), stdev = 0.010
  CI (99.9%): [2.895, 3.245] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.280 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.012 ms/op
Iteration   1: 4.127 ±(99.9%) 0.016 ms/op
Iteration   2: 4.098 ±(99.9%) 0.019 ms/op
Iteration   3: 4.082 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.103 ±(99.9%) 0.420 ms/op [Average]
  (min, avg, max) = (4.082, 4.103, 4.127), stdev = 0.023
  CI (99.9%): [3.682, 4.523] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.306 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.007 ms/op
Iteration   1: 3.096 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.282 ms/op
                 createUser·p0.9999: 13.675 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  9.754 ms/op
                 createUser·p0.9999: 22.981 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  10.061 ms/op
                 createUser·p0.9999: 18.711 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309407
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17716 
    [ 2.500,  5.000) = 289209 
    [ 5.000,  7.500) = 1750 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =      9.562 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     23.259 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.938 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 2.951 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.397 ms/op
                 existUser·p0.999:  7.356 ms/op
                 existUser·p0.9999: 15.321 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  9.363 ms/op
                 existUser·p0.9999: 14.908 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.608 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  10.331 ms/op
                 existUser·p0.9999: 29.932 ms/op
                 existUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319506
  mean =      3.004 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25992 
    [ 2.500,  5.000) = 291571 
    [ 5.000,  7.500) = 1209 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     29.196 ms/op
     p(99.9990) =     30.238 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.393 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
Iteration   1: 3.116 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  9.214 ms/op
                 getUser·p0.9999: 18.628 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.552 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.865 ms/op
                 getUser·p0.9999: 23.423 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  8.210 ms/op
                 getUser·p0.9999: 16.091 ms/op
                 getUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308926
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12921 
    [ 2.500,  5.000) = 294013 
    [ 5.000,  7.500) = 1365 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     21.827 ms/op
     p(99.9990) =     23.584 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 5.659 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.408 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.013 ms/op
Iteration   1: 4.142 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.193 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  15.237 ms/op
                 listUser·p0.9999: 20.770 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   2: 4.057 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  19.005 ms/op
                 listUser·p0.9999: 29.432 ms/op
                 listUser·p1.00:   30.212 ms/op

Iteration   3: 4.037 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  16.018 ms/op
                 listUser·p0.9999: 18.809 ms/op
                 listUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235613
  mean =      4.078 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2286 
    [ 2.500,  5.000) = 207758 
    [ 5.000,  7.500) = 23582 
    [ 7.500, 10.000) = 1350 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     16.266 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     30.090 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.395 ± 1.856  ops/ms
ClientGrpc.existUser                       thrpt       3  10.812 ± 3.239  ops/ms
ClientGrpc.getUser                         thrpt       3  10.296 ± 1.584  ops/ms
ClientGrpc.listUser                        thrpt       3   7.879 ± 2.213  ops/ms
ClientGrpc.createUser                       avgt       3   3.103 ± 0.406   ms/op
ClientGrpc.existUser                        avgt       3   2.913 ± 1.044   ms/op
ClientGrpc.getUser                          avgt       3   3.070 ± 0.175   ms/op
ClientGrpc.listUser                         avgt       3   4.103 ± 0.420   ms/op
ClientGrpc.createUser                     sample  309407   3.105 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.666           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.562           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.381           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.298           ms/op
ClientGrpc.existUser                      sample  319506   3.004 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.608           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.781           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.196           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.310           ms/op
ClientGrpc.getUser                        sample  308926   3.106 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.552           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.815           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.827           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.281           ms/op
ClientGrpc.listUser                       sample  235613   4.078 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.816           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.340           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.266           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.951           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.212           ms/op
