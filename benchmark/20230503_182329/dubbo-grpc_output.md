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
# Warmup Iteration   1: 4.313 ops/ms
# Warmup Iteration   2: 9.056 ops/ms
# Warmup Iteration   3: 9.943 ops/ms
Iteration   1: 10.664 ops/ms
Iteration   2: 10.678 ops/ms
Iteration   3: 10.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.639 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (10.574, 10.639, 10.678), stdev = 0.057
  CI (99.9%): [9.608, 11.669] (assumes normal distribution)


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
# Warmup Iteration   1: 7.391 ops/ms
# Warmup Iteration   2: 10.624 ops/ms
# Warmup Iteration   3: 11.137 ops/ms
Iteration   1: 11.302 ops/ms
Iteration   2: 10.963 ops/ms
Iteration   3: 11.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.199 ±(99.9%) 3.738 ops/ms [Average]
  (min, avg, max) = (10.963, 11.199, 11.331), stdev = 0.205
  CI (99.9%): [7.461, 14.937] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.558 ops/ms
# Warmup Iteration   2: 9.933 ops/ms
# Warmup Iteration   3: 10.572 ops/ms
Iteration   1: 10.573 ops/ms
Iteration   2: 10.762 ops/ms
Iteration   3: 10.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.702 ±(99.9%) 2.046 ops/ms [Average]
  (min, avg, max) = (10.573, 10.702, 10.772), stdev = 0.112
  CI (99.9%): [8.657, 12.748] (assumes normal distribution)


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
# Warmup Iteration   2: 7.647 ops/ms
# Warmup Iteration   3: 8.152 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 8.021 ops/ms
Iteration   3: 7.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.990 ±(99.9%) 1.095 ops/ms [Average]
  (min, avg, max) = (7.921, 7.990, 8.029), stdev = 0.060
  CI (99.9%): [6.895, 9.086] (assumes normal distribution)


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
# Warmup Iteration   1: 4.697 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.004 ms/op
Iteration   1: 3.070 ±(99.9%) 0.002 ms/op
Iteration   2: 3.058 ±(99.9%) 0.003 ms/op
Iteration   3: 3.054 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.061 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (3.054, 3.061, 3.070), stdev = 0.008
  CI (99.9%): [2.909, 3.212] (assumes normal distribution)


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
# Warmup Iteration   1: 4.160 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.003 ms/op
Iteration   1: 2.893 ±(99.9%) 0.001 ms/op
Iteration   2: 2.935 ±(99.9%) 0.002 ms/op
Iteration   3: 2.908 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.912 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (2.893, 2.912, 2.935), stdev = 0.021
  CI (99.9%): [2.521, 3.303] (assumes normal distribution)


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
# Warmup Iteration   1: 4.191 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.004 ms/op
Iteration   1: 3.030 ±(99.9%) 0.003 ms/op
Iteration   2: 2.984 ±(99.9%) 0.004 ms/op
Iteration   3: 2.992 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.002 ±(99.9%) 0.444 ms/op [Average]
  (min, avg, max) = (2.984, 3.002, 3.030), stdev = 0.024
  CI (99.9%): [2.558, 3.446] (assumes normal distribution)


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
# Warmup Iteration   1: 5.227 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.027 ms/op
Iteration   1: 3.871 ±(99.9%) 0.020 ms/op
Iteration   2: 3.894 ±(99.9%) 0.014 ms/op
Iteration   3: 3.890 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.885 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (3.871, 3.885, 3.894), stdev = 0.012
  CI (99.9%): [3.668, 4.102] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.473 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 2.995 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.866 ms/op
                 createUser·p0.9999: 12.151 ms/op
                 createUser·p1.00:   12.616 ms/op

Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.226 ms/op
                 createUser·p0.9999: 19.047 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  10.937 ms/op
                 createUser·p0.9999: 19.553 ms/op
                 createUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320814
  mean =      2.995 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25106 
    [ 2.500,  5.000) = 294212 
    [ 5.000,  7.500) = 1120 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.578 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     21.148 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.005 ms/op
Iteration   1: 2.861 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.656 ms/op
                 existUser·p0.9999: 13.222 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   2: 2.904 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  7.315 ms/op
                 existUser·p0.9999: 15.794 ms/op
                 existUser·p1.00:   16.056 ms/op

Iteration   3: 2.820 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  6.237 ms/op
                 existUser·p0.9999: 25.657 ms/op
                 existUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335255
  mean =      2.861 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49150 
    [ 2.500,  5.000) = 285073 
    [ 5.000,  7.500) = 782 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      7.010 ms/op
     p(99.9900) =     16.056 ms/op
     p(99.9990) =     25.908 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 4.137 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  6.234 ms/op
                 getUser·p0.9999: 19.891 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.818 ms/op
                 getUser·p0.9999: 21.330 ms/op
                 getUser·p1.00:   21.758 ms/op

Iteration   3: 3.000 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  8.124 ms/op
                 getUser·p0.9999: 22.479 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316877
  mean =      3.029 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25451 
    [ 2.500,  5.000) = 290036 
    [ 5.000,  7.500) = 1144 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      6.874 ms/op
     p(99.9900) =     21.834 ms/op
     p(99.9990) =     22.664 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 5.188 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.011 ms/op
Iteration   1: 3.923 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.696 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   2: 3.949 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 26.598 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   3: 3.980 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.204 ms/op
                 listUser·p0.9999: 23.360 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242851
  mean =      3.951 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3241 
    [ 2.500,  5.000) = 216207 
    [ 5.000,  7.500) = 22135 
    [ 7.500, 10.000) = 784 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.601 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.639 ± 1.031  ops/ms
ClientGrpc.existUser                       thrpt       3  11.199 ± 3.738  ops/ms
ClientGrpc.getUser                         thrpt       3  10.702 ± 2.046  ops/ms
ClientGrpc.listUser                        thrpt       3   7.990 ± 1.095  ops/ms
ClientGrpc.createUser                       avgt       3   3.061 ± 0.151   ms/op
ClientGrpc.existUser                        avgt       3   2.912 ± 0.391   ms/op
ClientGrpc.getUser                          avgt       3   3.002 ± 0.444   ms/op
ClientGrpc.listUser                         avgt       3   3.885 ± 0.217   ms/op
ClientGrpc.createUser                     sample  320814   2.995 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.596           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.578           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.973           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.299           ms/op
ClientGrpc.existUser                      sample  335255   2.861 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.690           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.843           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.116           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.010           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.056           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.116           ms/op
ClientGrpc.getUser                        sample  316877   3.029 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.693           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.874           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.834           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  242851   3.951 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.850           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.601           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.707           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.001           ms/op
