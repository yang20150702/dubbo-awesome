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
# Warmup Iteration   1: 4.600 ops/ms
# Warmup Iteration   2: 9.381 ops/ms
# Warmup Iteration   3: 10.326 ops/ms
Iteration   1: 10.730 ops/ms
Iteration   2: 10.775 ops/ms
Iteration   3: 10.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.771 ±(99.9%) 0.702 ops/ms [Average]
  (min, avg, max) = (10.730, 10.771, 10.807), stdev = 0.038
  CI (99.9%): [10.069, 11.473] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.114 ops/ms
# Warmup Iteration   2: 11.172 ops/ms
# Warmup Iteration   3: 11.187 ops/ms
Iteration   1: 11.314 ops/ms
Iteration   2: 11.419 ops/ms
Iteration   3: 11.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.308 ±(99.9%) 2.093 ops/ms [Average]
  (min, avg, max) = (11.190, 11.308, 11.419), stdev = 0.115
  CI (99.9%): [9.215, 13.401] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.166 ops/ms
# Warmup Iteration   2: 10.391 ops/ms
# Warmup Iteration   3: 10.617 ops/ms
Iteration   1: 10.707 ops/ms
Iteration   2: 10.572 ops/ms
Iteration   3: 10.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.668 ±(99.9%) 1.527 ops/ms [Average]
  (min, avg, max) = (10.572, 10.668, 10.726), stdev = 0.084
  CI (99.9%): [9.141, 12.196] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.682 ops/ms
# Warmup Iteration   2: 8.047 ops/ms
# Warmup Iteration   3: 8.073 ops/ms
Iteration   1: 8.207 ops/ms
Iteration   2: 8.222 ops/ms
Iteration   3: 8.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.219 ±(99.9%) 0.199 ops/ms [Average]
  (min, avg, max) = (8.207, 8.219, 8.229), stdev = 0.011
  CI (99.9%): [8.021, 8.418] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.933 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 2.988 ±(99.9%) 0.003 ms/op
Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.010 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.988, 3.010, 3.031), stdev = 0.021
  CI (99.9%): [2.621, 3.399] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 2.995 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.801 ±(99.9%) 0.003 ms/op
Iteration   1: 2.819 ±(99.9%) 0.002 ms/op
Iteration   2: 2.884 ±(99.9%) 0.003 ms/op
Iteration   3: 2.833 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.846 ±(99.9%) 0.627 ms/op [Average]
  (min, avg, max) = (2.819, 2.846, 2.884), stdev = 0.034
  CI (99.9%): [2.219, 3.473] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.906 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.002 ms/op
Iteration   1: 2.974 ±(99.9%) 0.002 ms/op
Iteration   2: 3.016 ±(99.9%) 0.002 ms/op
Iteration   3: 3.045 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.012 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (2.974, 3.012, 3.045), stdev = 0.035
  CI (99.9%): [2.367, 3.656] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.148 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.018 ms/op
Iteration   1: 3.915 ±(99.9%) 0.017 ms/op
Iteration   2: 3.915 ±(99.9%) 0.014 ms/op
Iteration   3: 3.831 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.887 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (3.831, 3.887, 3.915), stdev = 0.049
  CI (99.9%): [3.000, 4.774] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.923 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 2.969 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  7.946 ms/op
                 createUser·p0.9999: 10.961 ms/op
                 createUser·p1.00:   11.485 ms/op

Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  10.387 ms/op
                 createUser·p0.9999: 13.349 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   3: 2.984 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.612 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.523 ms/op
                 createUser·p0.99:   4.047 ms/op
                 createUser·p0.999:  8.943 ms/op
                 createUser·p0.9999: 24.979 ms/op
                 createUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320807
  mean =      2.990 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23085 
    [ 2.500,  5.000) = 296644 
    [ 5.000,  7.500) = 670 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      8.900 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     25.068 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.834 ±(99.9%) 0.006 ms/op
Iteration   1: 2.850 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  6.092 ms/op
                 existUser·p0.9999: 13.579 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 2.865 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  6.813 ms/op
                 existUser·p0.9999: 16.005 ms/op
                 existUser·p1.00:   16.171 ms/op

Iteration   3: 2.888 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.177 ms/op
                 existUser·p0.999:  11.600 ms/op
                 existUser·p0.9999: 26.638 ms/op
                 existUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334631
  mean =      2.868 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41444 
    [ 2.500,  5.000) = 292123 
    [ 5.000,  7.500) = 699 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      7.945 ms/op
     p(99.9900) =     16.163 ms/op
     p(99.9990) =     26.739 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.063 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.372 ms/op
                 getUser·p0.9999: 24.066 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  9.020 ms/op
                 getUser·p0.9999: 14.702 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   3: 3.045 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  6.349 ms/op
                 getUser·p0.9999: 15.589 ms/op
                 getUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317278
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24051 
    [ 2.500,  5.000) = 292169 
    [ 5.000,  7.500) = 802 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.010 ms/op
     p(99.9900) =     23.405 ms/op
     p(99.9990) =     24.177 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 4.731 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.009 ms/op
Iteration   1: 3.878 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  12.099 ms/op
                 listUser·p0.9999: 18.309 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   2: 3.913 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  13.978 ms/op
                 listUser·p0.9999: 16.828 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   3: 3.706 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.575 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.054 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250565
  mean =      3.830 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5743 
    [ 2.500,  5.000) = 223074 
    [ 5.000,  7.500) = 20537 
    [ 7.500, 10.000) = 734 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     13.802 ms/op
     p(99.9900) =     18.381 ms/op
     p(99.9990) =     22.806 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.771 ± 0.702  ops/ms
ClientGrpc.existUser                       thrpt       3  11.308 ± 2.093  ops/ms
ClientGrpc.getUser                         thrpt       3  10.668 ± 1.527  ops/ms
ClientGrpc.listUser                        thrpt       3   8.219 ± 0.199  ops/ms
ClientGrpc.createUser                       avgt       3   3.010 ± 0.389   ms/op
ClientGrpc.existUser                        avgt       3   2.846 ± 0.627   ms/op
ClientGrpc.getUser                          avgt       3   3.012 ± 0.644   ms/op
ClientGrpc.listUser                         avgt       3   3.887 ± 0.887   ms/op
ClientGrpc.createUser                     sample  320807   2.990 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.603           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.441           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.162           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.900           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.396           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.330           ms/op
ClientGrpc.existUser                      sample  334631   2.868 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.529           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.945           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.163           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.771           ms/op
ClientGrpc.getUser                        sample  317278   3.024 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.705           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.010           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.405           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.216           ms/op
ClientGrpc.listUser                       sample  250565   3.830 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.872           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.695           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.802           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.381           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.872           ms/op
