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
# Warmup Iteration   1: 4.428 ops/ms
# Warmup Iteration   2: 8.965 ops/ms
# Warmup Iteration   3: 10.042 ops/ms
Iteration   1: 10.363 ops/ms
Iteration   2: 10.832 ops/ms
Iteration   3: 10.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.578 ±(99.9%) 4.316 ops/ms [Average]
  (min, avg, max) = (10.363, 10.578, 10.832), stdev = 0.237
  CI (99.9%): [6.262, 14.894] (assumes normal distribution)


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
# Warmup Iteration   1: 7.507 ops/ms
# Warmup Iteration   2: 10.818 ops/ms
# Warmup Iteration   3: 11.084 ops/ms
Iteration   1: 11.120 ops/ms
Iteration   2: 10.927 ops/ms
Iteration   3: 11.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.036 ±(99.9%) 1.807 ops/ms [Average]
  (min, avg, max) = (10.927, 11.036, 11.120), stdev = 0.099
  CI (99.9%): [9.229, 12.843] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.053 ops/ms
# Warmup Iteration   2: 10.212 ops/ms
# Warmup Iteration   3: 10.500 ops/ms
Iteration   1: 10.723 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.619 ±(99.9%) 1.695 ops/ms [Average]
  (min, avg, max) = (10.543, 10.619, 10.723), stdev = 0.093
  CI (99.9%): [8.924, 12.314] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.154 ops/ms
# Warmup Iteration   2: 7.956 ops/ms
# Warmup Iteration   3: 8.123 ops/ms
Iteration   1: 8.198 ops/ms
Iteration   2: 8.166 ops/ms
Iteration   3: 8.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.150 ±(99.9%) 1.038 ops/ms [Average]
  (min, avg, max) = (8.087, 8.150, 8.198), stdev = 0.057
  CI (99.9%): [7.113, 9.188] (assumes normal distribution)


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.004 ms/op
Iteration   1: 3.000 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.004 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (2.981, 3.004, 3.031), stdev = 0.025
  CI (99.9%): [2.542, 3.466] (assumes normal distribution)


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
# Warmup Iteration   1: 3.616 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.955 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.005 ms/op
Iteration   1: 2.880 ±(99.9%) 0.003 ms/op
Iteration   2: 2.885 ±(99.9%) 0.002 ms/op
Iteration   3: 2.766 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.843 ±(99.9%) 1.232 ms/op [Average]
  (min, avg, max) = (2.766, 2.843, 2.885), stdev = 0.068
  CI (99.9%): [1.611, 4.076] (assumes normal distribution)


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.001 ms/op
Iteration   1: 3.004 ±(99.9%) 0.005 ms/op
Iteration   2: 2.960 ±(99.9%) 0.003 ms/op
Iteration   3: 2.989 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.984 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (2.960, 2.984, 3.004), stdev = 0.022
  CI (99.9%): [2.585, 3.384] (assumes normal distribution)


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
# Warmup Iteration   1: 5.605 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.017 ms/op
Iteration   1: 3.905 ±(99.9%) 0.023 ms/op
Iteration   2: 3.979 ±(99.9%) 0.016 ms/op
Iteration   3: 3.974 ±(99.9%) 0.051 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.953 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (3.905, 3.953, 3.979), stdev = 0.041
  CI (99.9%): [3.198, 4.707] (assumes normal distribution)


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
# Warmup Iteration   1: 4.388 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
Iteration   1: 3.041 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  9.975 ms/op
                 createUser·p0.9999: 22.807 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  9.612 ms/op
                 createUser·p0.9999: 17.776 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.425 ms/op
                 createUser·p0.9999: 23.152 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314923
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22932 
    [ 2.500,  5.000) = 290102 
    [ 5.000,  7.500) = 1445 
    [ 7.500, 10.000) = 183 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      8.835 ms/op
     p(99.9900) =     22.889 ms/op
     p(99.9990) =     24.894 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 4.108 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.883 ±(99.9%) 0.006 ms/op
Iteration   1: 2.898 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.826 ms/op
                 existUser·p0.9999: 18.840 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   2: 2.861 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  8.505 ms/op
                 existUser·p0.9999: 30.200 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   3: 2.903 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  11.829 ms/op
                 existUser·p0.9999: 17.367 ms/op
                 existUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332409
  mean =      2.887 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42298 
    [ 2.500,  5.000) = 288863 
    [ 5.000,  7.500) = 818 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.465 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      9.394 ms/op
     p(99.9900) =     19.063 ms/op
     p(99.9990) =     30.519 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 4.293 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  7.531 ms/op
                 getUser·p0.9999: 12.239 ms/op
                 getUser·p1.00:   12.403 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  8.773 ms/op
                 getUser·p0.9999: 13.384 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.472 ms/op
                 getUser·p0.9999: 20.513 ms/op
                 getUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317034
  mean =      3.027 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17224 
    [ 2.500,  5.000) = 298599 
    [ 5.000,  7.500) = 898 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.430 ms/op
     p(99.9900) =     19.847 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 4.654 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.010 ms/op
Iteration   1: 3.945 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.187 ms/op
                 listUser·p0.9999: 19.064 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   2: 3.948 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.382 ms/op
                 listUser·p0.9999: 16.522 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   3: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 24.203 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243460
  mean =      3.945 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3332 
    [ 2.500,  5.000) = 218218 
    [ 5.000,  7.500) = 20730 
    [ 7.500, 10.000) = 738 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.591 ms/op
     p(99.9900) =     21.287 ms/op
     p(99.9990) =     24.674 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.578 ± 4.316  ops/ms
ClientGrpc.existUser                       thrpt       3  11.036 ± 1.807  ops/ms
ClientGrpc.getUser                         thrpt       3  10.619 ± 1.695  ops/ms
ClientGrpc.listUser                        thrpt       3   8.150 ± 1.038  ops/ms
ClientGrpc.createUser                       avgt       3   3.004 ± 0.462   ms/op
ClientGrpc.existUser                        avgt       3   2.843 ± 1.232   ms/op
ClientGrpc.getUser                          avgt       3   2.984 ± 0.400   ms/op
ClientGrpc.listUser                         avgt       3   3.953 ± 0.754   ms/op
ClientGrpc.createUser                     sample  314923   3.046 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.691           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.835           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.889           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.166           ms/op
ClientGrpc.existUser                      sample  332409   2.887 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.529           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.293           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.394           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.063           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.605           ms/op
ClientGrpc.getUser                        sample  317034   3.027 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.794           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.430           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.847           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.906           ms/op
ClientGrpc.listUser                       sample  243460   3.945 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.936           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.591           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.287           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.707           ms/op
