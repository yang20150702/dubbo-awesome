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
# Warmup Iteration   1: 3.974 ops/ms
# Warmup Iteration   2: 8.909 ops/ms
# Warmup Iteration   3: 9.795 ops/ms
Iteration   1: 10.244 ops/ms
Iteration   2: 10.384 ops/ms
Iteration   3: 10.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.351 ±(99.9%) 1.747 ops/ms [Average]
  (min, avg, max) = (10.244, 10.351, 10.426), stdev = 0.096
  CI (99.9%): [8.605, 12.098] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.223 ops/ms
# Warmup Iteration   2: 10.593 ops/ms
# Warmup Iteration   3: 10.991 ops/ms
Iteration   1: 10.931 ops/ms
Iteration   2: 11.104 ops/ms
Iteration   3: 11.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.095 ±(99.9%) 2.912 ops/ms [Average]
  (min, avg, max) = (10.931, 11.095, 11.250), stdev = 0.160
  CI (99.9%): [8.183, 14.007] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.382 ops/ms
# Warmup Iteration   2: 10.024 ops/ms
# Warmup Iteration   3: 10.112 ops/ms
Iteration   1: 10.440 ops/ms
Iteration   2: 10.323 ops/ms
Iteration   3: 10.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.383 ±(99.9%) 1.067 ops/ms [Average]
  (min, avg, max) = (10.323, 10.383, 10.440), stdev = 0.058
  CI (99.9%): [9.316, 11.450] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.723 ops/ms
# Warmup Iteration   2: 7.458 ops/ms
# Warmup Iteration   3: 7.729 ops/ms
Iteration   1: 7.884 ops/ms
Iteration   2: 7.908 ops/ms
Iteration   3: 7.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.886 ±(99.9%) 0.396 ops/ms [Average]
  (min, avg, max) = (7.865, 7.886, 7.908), stdev = 0.022
  CI (99.9%): [7.490, 8.281] (assumes normal distribution)


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
# Warmup Iteration   1: 4.469 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.003 ms/op
Iteration   1: 3.119 ±(99.9%) 0.004 ms/op
Iteration   2: 3.116 ±(99.9%) 0.003 ms/op
Iteration   3: 3.052 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.096 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (3.052, 3.096, 3.119), stdev = 0.038
  CI (99.9%): [2.400, 3.792] (assumes normal distribution)


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
# Warmup Iteration   1: 4.202 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.002 ms/op
Iteration   1: 2.948 ±(99.9%) 0.004 ms/op
Iteration   2: 2.897 ±(99.9%) 0.002 ms/op
Iteration   3: 2.953 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.933 ±(99.9%) 0.573 ms/op [Average]
  (min, avg, max) = (2.897, 2.933, 2.953), stdev = 0.031
  CI (99.9%): [2.360, 3.505] (assumes normal distribution)


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
# Warmup Iteration   1: 4.407 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.002 ms/op
Iteration   1: 3.075 ±(99.9%) 0.004 ms/op
Iteration   2: 3.102 ±(99.9%) 0.003 ms/op
Iteration   3: 3.055 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.077 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (3.055, 3.077, 3.102), stdev = 0.024
  CI (99.9%): [2.645, 3.510] (assumes normal distribution)


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
# Warmup Iteration   1: 5.751 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.029 ms/op
Iteration   1: 4.084 ±(99.9%) 0.016 ms/op
Iteration   2: 4.035 ±(99.9%) 0.029 ms/op
Iteration   3: 4.086 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.068 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (4.035, 4.068, 4.086), stdev = 0.029
  CI (99.9%): [3.541, 4.596] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.311 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  8.503 ms/op
                 createUser·p0.9999: 12.796 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   2: 3.068 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.454 ms/op
                 createUser·p0.9999: 15.634 ms/op
                 createUser·p1.00:   16.237 ms/op

Iteration   3: 3.083 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  14.617 ms/op
                 createUser·p0.9999: 26.202 ms/op
                 createUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312323
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18141 
    [ 2.500,  5.000) = 291904 
    [ 5.000,  7.500) = 1627 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      9.413 ms/op
     p(99.9900) =     19.056 ms/op
     p(99.9990) =     26.440 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.006 ms/op
Iteration   1: 2.964 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  8.472 ms/op
                 existUser·p0.9999: 17.007 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 2.952 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.285 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.343 ms/op
                 existUser·p0.999:  7.204 ms/op
                 existUser·p0.9999: 33.036 ms/op
                 existUser·p1.00:   34.406 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  8.339 ms/op
                 existUser·p0.9999: 17.406 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324192
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32289 
    [ 2.500,  5.000) = 290083 
    [ 5.000,  7.500) = 1339 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.285 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.564 ms/op
     p(99.9000) =      8.061 ms/op
     p(99.9900) =     26.016 ms/op
     p(99.9990) =     34.325 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
Iteration   1: 3.125 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.433 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  8.197 ms/op
                 getUser·p0.9999: 22.536 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 16.796 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  8.946 ms/op
                 getUser·p0.9999: 17.021 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312360
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21139 
    [ 2.500,  5.000) = 288545 
    [ 5.000,  7.500) = 2074 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =      8.989 ms/op
     p(99.9900) =     21.833 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 5.789 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.143 ±(99.9%) 0.012 ms/op
Iteration   1: 4.101 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   2: 4.088 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  25.919 ms/op
                 listUser·p0.9999: 28.525 ms/op
                 listUser·p1.00:   29.131 ms/op

Iteration   3: 4.089 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  16.748 ms/op
                 listUser·p0.9999: 20.780 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234588
  mean =      4.093 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2651 
    [ 2.500,  5.000) = 205805 
    [ 5.000,  7.500) = 23829 
    [ 7.500, 10.000) = 1724 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      6.054 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     27.412 ms/op
     p(99.9990) =     29.010 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.351 ± 1.747  ops/ms
ClientGrpc.existUser                       thrpt       3  11.095 ± 2.912  ops/ms
ClientGrpc.getUser                         thrpt       3  10.383 ± 1.067  ops/ms
ClientGrpc.listUser                        thrpt       3   7.886 ± 0.396  ops/ms
ClientGrpc.createUser                       avgt       3   3.096 ± 0.696   ms/op
ClientGrpc.existUser                        avgt       3   2.933 ± 0.573   ms/op
ClientGrpc.getUser                          avgt       3   3.077 ± 0.432   ms/op
ClientGrpc.listUser                         avgt       3   4.068 ± 0.527   ms/op
ClientGrpc.createUser                     sample  312323   3.074 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.799           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.413           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.056           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.656           ms/op
ClientGrpc.existUser                      sample  324192   2.961 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.285           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.564           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.061           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.016           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.406           ms/op
ClientGrpc.getUser                        sample  312360   3.075 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.433           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.989           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.833           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  234588   4.093 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.971           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.054           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.479           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.024           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.412           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.131           ms/op
