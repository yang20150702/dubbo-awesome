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
# Warmup Iteration   1: 3.477 ops/ms
# Warmup Iteration   2: 7.845 ops/ms
# Warmup Iteration   3: 9.611 ops/ms
Iteration   1: 9.757 ops/ms
Iteration   2: 10.045 ops/ms
Iteration   3: 10.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.970 ±(99.9%) 3.403 ops/ms [Average]
  (min, avg, max) = (9.757, 9.970, 10.106), stdev = 0.187
  CI (99.9%): [6.566, 13.373] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.445 ops/ms
# Warmup Iteration   2: 9.972 ops/ms
# Warmup Iteration   3: 10.246 ops/ms
Iteration   1: 10.082 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.422 ±(99.9%) 5.388 ops/ms [Average]
  (min, avg, max) = (10.082, 10.422, 10.617), stdev = 0.295
  CI (99.9%): [5.034, 15.809] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.354 ops/ms
# Warmup Iteration   2: 9.728 ops/ms
# Warmup Iteration   3: 9.861 ops/ms
Iteration   1: 9.919 ops/ms
Iteration   2: 9.833 ops/ms
Iteration   3: 9.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.864 ±(99.9%) 0.873 ops/ms [Average]
  (min, avg, max) = (9.833, 9.864, 9.919), stdev = 0.048
  CI (99.9%): [8.991, 10.737] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.269 ops/ms
# Warmup Iteration   2: 7.434 ops/ms
# Warmup Iteration   3: 7.640 ops/ms
Iteration   1: 7.694 ops/ms
Iteration   2: 8.018 ops/ms
Iteration   3: 7.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.860 ±(99.9%) 2.959 ops/ms [Average]
  (min, avg, max) = (7.694, 7.860, 8.018), stdev = 0.162
  CI (99.9%): [4.901, 10.819] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.903 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.003 ms/op
Iteration   1: 3.162 ±(99.9%) 0.003 ms/op
Iteration   2: 3.216 ±(99.9%) 0.004 ms/op
Iteration   3: 3.269 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.216 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (3.162, 3.216, 3.269), stdev = 0.053
  CI (99.9%): [2.241, 4.190] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.374 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.003 ms/op
Iteration   1: 3.032 ±(99.9%) 0.003 ms/op
Iteration   2: 3.073 ±(99.9%) 0.003 ms/op
Iteration   3: 3.037 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.047 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (3.032, 3.047, 3.073), stdev = 0.023
  CI (99.9%): [2.637, 3.458] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.527 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.003 ms/op
Iteration   1: 3.225 ±(99.9%) 0.003 ms/op
Iteration   2: 3.239 ±(99.9%) 0.006 ms/op
Iteration   3: 3.268 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.244 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (3.225, 3.244, 3.268), stdev = 0.022
  CI (99.9%): [2.848, 3.640] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.015 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.583 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.022 ms/op
Iteration   1: 4.096 ±(99.9%) 0.020 ms/op
Iteration   2: 4.055 ±(99.9%) 0.027 ms/op
Iteration   3: 4.108 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.087 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (4.055, 4.087, 4.108), stdev = 0.028
  CI (99.9%): [3.581, 4.592] (assumes normal distribution)


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
# Warmup Iteration   1: 4.909 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.008 ms/op
Iteration   1: 3.221 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  11.463 ms/op
                 createUser·p0.9999: 16.270 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 3.275 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  8.097 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  13.455 ms/op
                 createUser·p0.9999: 17.564 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297941
  mean =      3.224 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8595 
    [ 2.500,  5.000) = 287150 
    [ 5.000,  7.500) = 1647 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     20.376 ms/op
     p(99.9990) =     22.944 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.166 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
Iteration   1: 3.104 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  8.012 ms/op
                 existUser·p0.9999: 22.918 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   2: 3.156 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.792 ms/op
                 existUser·p0.999:  7.927 ms/op
                 existUser·p0.9999: 15.481 ms/op
                 existUser·p1.00:   15.991 ms/op

Iteration   3: 3.137 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  13.123 ms/op
                 existUser·p0.9999: 27.184 ms/op
                 existUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 306334
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13091 
    [ 2.500,  5.000) = 291176 
    [ 5.000,  7.500) = 1569 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =     11.119 ms/op
     p(99.9900) =     22.732 ms/op
     p(99.9990) =     27.949 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.719 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.006 ms/op
Iteration   1: 3.254 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.342 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  11.495 ms/op
                 getUser·p0.9999: 19.043 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 3.252 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.433 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  14.231 ms/op
                 getUser·p0.9999: 25.269 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   3: 3.171 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  8.135 ms/op
                 getUser·p0.9999: 16.348 ms/op
                 getUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297835
  mean =      3.225 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8804 
    [ 2.500,  5.000) = 286811 
    [ 5.000,  7.500) = 1653 
    [ 7.500, 10.000) = 268 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.342 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =     10.832 ms/op
     p(99.9900) =     19.458 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 5.685 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.010 ms/op
Iteration   1: 4.130 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  14.530 ms/op
                 listUser·p0.9999: 24.740 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   2: 4.104 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.518 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.159 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 17.407 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   3: 4.159 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  19.366 ms/op
                 listUser·p0.9999: 23.658 ms/op
                 listUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232366
  mean =      4.131 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1816 
    [ 2.500,  5.000) = 209400 
    [ 5.000,  7.500) = 19351 
    [ 7.500, 10.000) = 1038 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     16.169 ms/op
     p(99.9900) =     23.618 ms/op
     p(99.9990) =     24.860 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.970 ± 3.403  ops/ms
ClientGrpc.existUser                       thrpt       3  10.422 ± 5.388  ops/ms
ClientGrpc.getUser                         thrpt       3   9.864 ± 0.873  ops/ms
ClientGrpc.listUser                        thrpt       3   7.860 ± 2.959  ops/ms
ClientGrpc.createUser                       avgt       3   3.216 ± 0.974   ms/op
ClientGrpc.existUser                        avgt       3   3.047 ± 0.411   ms/op
ClientGrpc.getUser                          avgt       3   3.244 ± 0.396   ms/op
ClientGrpc.listUser                         avgt       3   4.087 ± 0.506   ms/op
ClientGrpc.createUser                     sample  297941   3.224 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.745           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.183           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.567           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.376           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.724           ms/op
ClientGrpc.existUser                      sample  306334   3.132 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.767           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.072           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.953           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.119           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.732           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.049           ms/op
ClientGrpc.getUser                        sample  297835   3.225 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.342           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.178           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.994           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.832           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.458           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.723           ms/op
ClientGrpc.listUser                       sample  232366   4.131 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.938           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.998           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.169           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.618           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.035           ms/op
