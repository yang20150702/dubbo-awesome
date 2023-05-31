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
# Warmup Iteration   1: 3.931 ops/ms
# Warmup Iteration   2: 9.170 ops/ms
# Warmup Iteration   3: 9.832 ops/ms
Iteration   1: 10.480 ops/ms
Iteration   2: 10.407 ops/ms
Iteration   3: 10.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.508 ±(99.9%) 2.155 ops/ms [Average]
  (min, avg, max) = (10.407, 10.508, 10.638), stdev = 0.118
  CI (99.9%): [8.353, 12.664] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.036 ops/ms
# Warmup Iteration   2: 10.348 ops/ms
# Warmup Iteration   3: 10.800 ops/ms
Iteration   1: 10.835 ops/ms
Iteration   2: 11.238 ops/ms
Iteration   3: 10.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.949 ±(99.9%) 4.613 ops/ms [Average]
  (min, avg, max) = (10.773, 10.949, 11.238), stdev = 0.253
  CI (99.9%): [6.336, 15.561] (assumes normal distribution)


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
# Warmup Iteration   1: 6.754 ops/ms
# Warmup Iteration   2: 10.088 ops/ms
# Warmup Iteration   3: 10.223 ops/ms
Iteration   1: 10.359 ops/ms
Iteration   2: 10.358 ops/ms
Iteration   3: 10.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.375 ±(99.9%) 0.522 ops/ms [Average]
  (min, avg, max) = (10.358, 10.375, 10.408), stdev = 0.029
  CI (99.9%): [9.853, 10.897] (assumes normal distribution)


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
# Warmup Iteration   1: 5.500 ops/ms
# Warmup Iteration   2: 7.461 ops/ms
# Warmup Iteration   3: 7.752 ops/ms
Iteration   1: 7.949 ops/ms
Iteration   2: 7.913 ops/ms
Iteration   3: 7.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.928 ±(99.9%) 0.342 ops/ms [Average]
  (min, avg, max) = (7.913, 7.928, 7.949), stdev = 0.019
  CI (99.9%): [7.585, 8.270] (assumes normal distribution)


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
# Warmup Iteration   1: 4.675 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.003 ms/op
Iteration   1: 2.962 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 3.022 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.010 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (2.962, 3.010, 3.047), stdev = 0.044
  CI (99.9%): [2.211, 3.810] (assumes normal distribution)


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.002 ms/op
Iteration   1: 2.910 ±(99.9%) 0.002 ms/op
Iteration   2: 2.944 ±(99.9%) 0.002 ms/op
Iteration   3: 2.912 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.922 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (2.910, 2.922, 2.944), stdev = 0.019
  CI (99.9%): [2.574, 3.270] (assumes normal distribution)


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
# Warmup Iteration   1: 4.502 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.002 ms/op
Iteration   2: 3.037 ±(99.9%) 0.002 ms/op
Iteration   3: 3.095 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.077 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (3.037, 3.077, 3.098), stdev = 0.034
  CI (99.9%): [2.452, 3.702] (assumes normal distribution)


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
# Warmup Iteration   1: 5.625 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.011 ms/op
Iteration   1: 3.949 ±(99.9%) 0.011 ms/op
Iteration   2: 3.995 ±(99.9%) 0.020 ms/op
Iteration   3: 3.989 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.978 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.949, 3.978, 3.995), stdev = 0.025
  CI (99.9%): [3.517, 4.438] (assumes normal distribution)


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
# Warmup Iteration   1: 4.499 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.073 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.110 ms/op
                 createUser·p0.9999: 13.143 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.533 ms/op
                 createUser·p0.999:  8.042 ms/op
                 createUser·p0.9999: 14.423 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   3: 3.001 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  12.190 ms/op
                 createUser·p0.9999: 33.522 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316277
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25877 
    [ 2.500,  5.000) = 288601 
    [ 5.000,  7.500) = 1297 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     32.616 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.005 ms/op
Iteration   1: 2.949 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.709 ms/op
                 existUser·p0.9999: 12.871 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  10.243 ms/op
                 existUser·p0.9999: 14.881 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   3: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  6.634 ms/op
                 existUser·p0.9999: 17.009 ms/op
                 existUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325191
  mean =      2.954 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1563 
    [ 1.250,  2.500) = 25931 
    [ 2.500,  3.750) = 286636 
    [ 3.750,  5.000) = 9793 
    [ 5.000,  6.250) = 733 
    [ 6.250,  7.500) = 265 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.929 ms/op
     p(99.9900) =     16.466 ms/op
     p(99.9990) =     17.408 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
Iteration   1: 3.087 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.807 ms/op
                 getUser·p0.9999: 13.647 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  7.571 ms/op
                 getUser·p0.9999: 15.624 ms/op
                 getUser·p1.00:   16.810 ms/op

Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.791 ms/op
                 getUser·p0.9999: 29.622 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311081
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18603 
    [ 2.500,  5.000) = 290593 
    [ 5.000,  7.500) = 1616 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      7.151 ms/op
     p(99.9900) =     28.698 ms/op
     p(99.9990) =     29.975 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 5.372 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.011 ms/op
Iteration   1: 4.025 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  15.311 ms/op
                 listUser·p0.9999: 17.039 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   2: 4.073 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  15.381 ms/op
                 listUser·p0.9999: 17.624 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 3.910 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 18.437 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239788
  mean =      4.002 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 2050 
    [ 2.500,  3.750) = 93974 
    [ 3.750,  5.000) = 121191 
    [ 5.000,  6.250) = 16046 
    [ 6.250,  7.500) = 5224 
    [ 7.500,  8.750) = 703 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 123 
    [16.250, 17.500) = 129 
    [17.500, 18.750) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     18.056 ms/op
     p(99.9990) =     19.216 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.508 ± 2.155  ops/ms
ClientGrpc.existUser                       thrpt       3  10.949 ± 4.613  ops/ms
ClientGrpc.getUser                         thrpt       3  10.375 ± 0.522  ops/ms
ClientGrpc.listUser                        thrpt       3   7.928 ± 0.342  ops/ms
ClientGrpc.createUser                       avgt       3   3.010 ± 0.799   ms/op
ClientGrpc.existUser                        avgt       3   2.922 ± 0.348   ms/op
ClientGrpc.getUser                          avgt       3   3.077 ± 0.625   ms/op
ClientGrpc.listUser                         avgt       3   3.978 ± 0.460   ms/op
ClientGrpc.createUser                     sample  316277   3.035 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.787           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.569           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.616           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.554           ms/op
ClientGrpc.existUser                      sample  325191   2.954 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.590           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.929           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.466           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.695           ms/op
ClientGrpc.getUser                        sample  311081   3.085 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.676           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.151           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.698           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.048           ms/op
ClientGrpc.listUser                       sample  239788   4.002 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.149           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.565           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.056           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.595           ms/op
