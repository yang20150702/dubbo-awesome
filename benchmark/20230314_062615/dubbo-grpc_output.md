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
# Warmup Iteration   1: 2.508 ops/ms
# Warmup Iteration   2: 6.133 ops/ms
# Warmup Iteration   3: 7.697 ops/ms
Iteration   1: 7.859 ops/ms
Iteration   2: 8.048 ops/ms
Iteration   3: 8.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.009 ±(99.9%) 2.448 ops/ms [Average]
  (min, avg, max) = (7.859, 8.009, 8.119), stdev = 0.134
  CI (99.9%): [5.561, 10.457] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.226 ops/ms
# Warmup Iteration   2: 8.109 ops/ms
# Warmup Iteration   3: 8.566 ops/ms
Iteration   1: 8.789 ops/ms
Iteration   2: 8.506 ops/ms
Iteration   3: 8.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.691 ±(99.9%) 2.931 ops/ms [Average]
  (min, avg, max) = (8.506, 8.691, 8.789), stdev = 0.161
  CI (99.9%): [5.760, 11.623] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.600 ops/ms
# Warmup Iteration   2: 7.314 ops/ms
# Warmup Iteration   3: 7.889 ops/ms
Iteration   1: 7.805 ops/ms
Iteration   2: 7.968 ops/ms
Iteration   3: 8.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.022 ±(99.9%) 4.533 ops/ms [Average]
  (min, avg, max) = (7.805, 8.022, 8.293), stdev = 0.248
  CI (99.9%): [3.489, 12.555] (assumes normal distribution)


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
# Warmup Iteration   1: 4.117 ops/ms
# Warmup Iteration   2: 5.691 ops/ms
# Warmup Iteration   3: 6.449 ops/ms
Iteration   1: 6.165 ops/ms
Iteration   2: 6.372 ops/ms
Iteration   3: 6.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.301 ±(99.9%) 2.156 ops/ms [Average]
  (min, avg, max) = (6.165, 6.301, 6.372), stdev = 0.118
  CI (99.9%): [4.145, 8.458] (assumes normal distribution)


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
# Warmup Iteration   1: 5.888 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.004 ms/op
Iteration   1: 4.022 ±(99.9%) 0.003 ms/op
Iteration   2: 3.802 ±(99.9%) 0.003 ms/op
Iteration   3: 4.050 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.958 ±(99.9%) 2.478 ms/op [Average]
  (min, avg, max) = (3.802, 3.958, 4.050), stdev = 0.136
  CI (99.9%): [1.480, 6.436] (assumes normal distribution)


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
# Warmup Iteration   1: 5.762 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.003 ms/op
Iteration   1: 3.820 ±(99.9%) 0.002 ms/op
Iteration   2: 3.627 ±(99.9%) 0.003 ms/op
Iteration   3: 3.825 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.758 ±(99.9%) 2.056 ms/op [Average]
  (min, avg, max) = (3.627, 3.758, 3.825), stdev = 0.113
  CI (99.9%): [1.702, 5.814] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.077 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.003 ms/op
Iteration   1: 3.904 ±(99.9%) 0.003 ms/op
Iteration   2: 3.896 ±(99.9%) 0.003 ms/op
Iteration   3: 3.844 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.882 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (3.844, 3.882, 3.904), stdev = 0.033
  CI (99.9%): [3.286, 4.478] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.854 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.714 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.292 ±(99.9%) 0.030 ms/op
Iteration   1: 5.293 ±(99.9%) 0.027 ms/op
Iteration   2: 5.205 ±(99.9%) 0.020 ms/op
Iteration   3: 5.082 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.194 ±(99.9%) 1.935 ms/op [Average]
  (min, avg, max) = (5.082, 5.194, 5.293), stdev = 0.106
  CI (99.9%): [3.258, 7.129] (assumes normal distribution)


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
# Warmup Iteration   1: 6.259 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.274 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.012 ms/op
Iteration   1: 4.014 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   5.153 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   7.057 ms/op
                 createUser·p0.999:  12.474 ms/op
                 createUser·p0.9999: 28.182 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   2: 3.930 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.194 ms/op
                 createUser·p0.99:   6.053 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 28.631 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   3: 4.068 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   5.005 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  23.167 ms/op
                 createUser·p0.9999: 29.786 ms/op
                 createUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 239604
  mean =      4.003 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8465 
    [ 2.500,  5.000) = 207453 
    [ 5.000,  7.500) = 22431 
    [ 7.500, 10.000) = 965 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     10.528 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     29.957 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.121 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.009 ms/op
Iteration   1: 3.728 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.710 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  9.605 ms/op
                 existUser·p0.9999: 15.122 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   2: 3.848 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.710 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   6.321 ms/op
                 existUser·p0.999:  8.716 ms/op
                 existUser·p0.9999: 23.331 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 3.778 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   6.246 ms/op
                 existUser·p0.999:  9.048 ms/op
                 existUser·p0.9999: 18.633 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 253671
  mean =      3.784 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8371 
    [ 2.500,  5.000) = 231314 
    [ 5.000,  7.500) = 13052 
    [ 7.500, 10.000) = 749 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =      9.246 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     23.888 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 6.248 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.011 ms/op
Iteration   1: 3.982 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.899 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.456 ms/op
                 getUser·p0.99:   6.701 ms/op
                 getUser·p0.999:  9.748 ms/op
                 getUser·p0.9999: 15.024 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   2: 4.054 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   5.439 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  9.984 ms/op
                 getUser·p0.9999: 16.306 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   3: 3.984 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   6.317 ms/op
                 getUser·p0.999:  11.272 ms/op
                 getUser·p0.9999: 19.756 ms/op
                 getUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 239463
  mean =      4.006 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5678 
    [ 2.500,  5.000) = 210679 
    [ 5.000,  7.500) = 22025 
    [ 7.500, 10.000) = 844 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =      9.987 ms/op
     p(99.9900) =     17.509 ms/op
     p(99.9990) =     20.245 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 7.630 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.436 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.160 ±(99.9%) 0.017 ms/op
Iteration   1: 5.137 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   4.899 ms/op
                 listUser·p0.90:   6.595 ms/op
                 listUser·p0.95:   7.447 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  16.691 ms/op
                 listUser·p0.9999: 24.775 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   2: 5.162 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   9.334 ms/op
                 listUser·p0.999:  15.797 ms/op
                 listUser·p0.9999: 20.893 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 5.062 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   6.373 ms/op
                 listUser·p0.95:   7.365 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  19.587 ms/op
                 listUser·p0.9999: 27.265 ms/op
                 listUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 187295
  mean =      5.120 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 201 
    [ 2.500,  5.000) = 104300 
    [ 5.000,  7.500) = 74124 
    [ 7.500, 10.000) = 7482 
    [10.000, 12.500) = 755 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.406 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     18.439 ms/op
     p(99.9900) =     25.306 ms/op
     p(99.9990) =     27.738 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.009 ± 2.448  ops/ms
ClientGrpc.existUser                       thrpt       3   8.691 ± 2.931  ops/ms
ClientGrpc.getUser                         thrpt       3   8.022 ± 4.533  ops/ms
ClientGrpc.listUser                        thrpt       3   6.301 ± 2.156  ops/ms
ClientGrpc.createUser                       avgt       3   3.958 ± 2.478   ms/op
ClientGrpc.existUser                        avgt       3   3.758 ± 2.056   ms/op
ClientGrpc.getUser                          avgt       3   3.882 ± 0.596   ms/op
ClientGrpc.listUser                         avgt       3   5.194 ± 1.935   ms/op
ClientGrpc.createUser                     sample  239604   4.003 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.867           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.997           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.627           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.528           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.803           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.015           ms/op
ClientGrpc.existUser                      sample  253671   3.784 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.863           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.661           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.054           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.250           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.246           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.627           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.019           ms/op
ClientGrpc.getUser                        sample  239463   4.006 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.934           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.399           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.447           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.987           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.509           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.382           ms/op
ClientGrpc.listUser                       sample  187295   5.120 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.575           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.406           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.306           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.439           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.306           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.853           ms/op
