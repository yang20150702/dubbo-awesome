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
# Warmup Iteration   1: 3.888 ops/ms
# Warmup Iteration   2: 8.651 ops/ms
# Warmup Iteration   3: 9.710 ops/ms
Iteration   1: 9.904 ops/ms
Iteration   2: 9.996 ops/ms
Iteration   3: 9.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.856 ±(99.9%) 3.089 ops/ms [Average]
  (min, avg, max) = (9.668, 9.856, 9.996), stdev = 0.169
  CI (99.9%): [6.767, 12.945] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.946 ops/ms
# Warmup Iteration   2: 10.044 ops/ms
# Warmup Iteration   3: 10.157 ops/ms
Iteration   1: 10.301 ops/ms
Iteration   2: 9.935 ops/ms
Iteration   3: 10.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.315 ±(99.9%) 7.057 ops/ms [Average]
  (min, avg, max) = (9.935, 10.315, 10.708), stdev = 0.387
  CI (99.9%): [3.257, 17.372] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.516 ops/ms
# Warmup Iteration   2: 9.512 ops/ms
# Warmup Iteration   3: 9.893 ops/ms
Iteration   1: 9.948 ops/ms
Iteration   2: 9.991 ops/ms
Iteration   3: 9.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.904 ±(99.9%) 2.100 ops/ms [Average]
  (min, avg, max) = (9.774, 9.904, 9.991), stdev = 0.115
  CI (99.9%): [7.804, 12.004] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.326 ops/ms
# Warmup Iteration   2: 7.341 ops/ms
# Warmup Iteration   3: 7.587 ops/ms
Iteration   1: 7.747 ops/ms
Iteration   2: 7.589 ops/ms
Iteration   3: 7.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.609 ±(99.9%) 2.350 ops/ms [Average]
  (min, avg, max) = (7.492, 7.609, 7.747), stdev = 0.129
  CI (99.9%): [5.260, 9.959] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.874 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.005 ms/op
Iteration   1: 3.310 ±(99.9%) 0.009 ms/op
Iteration   2: 3.210 ±(99.9%) 0.002 ms/op
Iteration   3: 3.296 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.272 ±(99.9%) 0.986 ms/op [Average]
  (min, avg, max) = (3.210, 3.272, 3.310), stdev = 0.054
  CI (99.9%): [2.286, 4.258] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.185 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.004 ms/op
Iteration   1: 3.145 ±(99.9%) 0.002 ms/op
Iteration   2: 3.046 ±(99.9%) 0.002 ms/op
Iteration   3: 3.132 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.107 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (3.046, 3.107, 3.145), stdev = 0.054
  CI (99.9%): [2.123, 4.091] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.243 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.002 ms/op
Iteration   1: 3.192 ±(99.9%) 0.003 ms/op
Iteration   2: 3.200 ±(99.9%) 0.002 ms/op
Iteration   3: 3.301 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.231 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.192, 3.231, 3.301), stdev = 0.061
  CI (99.9%): [2.119, 4.343] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.579 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.273 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.011 ms/op
Iteration   1: 4.245 ±(99.9%) 0.008 ms/op
Iteration   2: 4.202 ±(99.9%) 0.013 ms/op
Iteration   3: 4.109 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.185 ±(99.9%) 1.267 ms/op [Average]
  (min, avg, max) = (4.109, 4.185, 4.245), stdev = 0.069
  CI (99.9%): [2.918, 5.453] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.354 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.008 ms/op
Iteration   1: 3.296 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  8.290 ms/op
                 createUser·p0.9999: 20.195 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   2: 3.225 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.458 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.387 ms/op
                 createUser·p0.9999: 18.518 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.842 ms/op
                 createUser·p0.9999: 21.795 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 295679
  mean =      3.245 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17788 
    [ 2.500,  5.000) = 276189 
    [ 5.000,  7.500) = 1129 
    [ 7.500, 10.000) = 345 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.492 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     22.252 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.007 ms/op
Iteration   1: 3.205 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  8.756 ms/op
                 existUser·p0.9999: 16.269 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   2: 3.083 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  9.062 ms/op
                 existUser·p0.9999: 25.657 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  7.894 ms/op
                 existUser·p0.9999: 18.022 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 306160
  mean =      3.137 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29265 
    [ 2.500,  5.000) = 274746 
    [ 5.000,  7.500) = 1614 
    [ 7.500, 10.000) = 276 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      8.832 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     25.915 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 4.719 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.007 ms/op
Iteration   1: 3.315 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  9.010 ms/op
                 getUser·p0.9999: 16.920 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   2: 3.312 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  8.189 ms/op
                 getUser·p0.9999: 15.232 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   3: 3.228 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.653 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  6.586 ms/op
                 getUser·p0.9999: 27.692 ms/op
                 getUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 292200
  mean =      3.284 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11440 
    [ 2.500,  5.000) = 278838 
    [ 5.000,  7.500) = 1636 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      7.419 ms/op
     p(99.9900) =     25.712 ms/op
     p(99.9990) =     28.052 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 4.834 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.339 ±(99.9%) 0.013 ms/op
Iteration   1: 4.291 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   7.547 ms/op
                 listUser·p0.999:  13.407 ms/op
                 listUser·p0.9999: 15.942 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   2: 4.157 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  16.593 ms/op
                 listUser·p0.9999: 19.768 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   3: 4.347 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   4.125 ms/op
                 listUser·p0.90:   5.661 ms/op
                 listUser·p0.95:   6.300 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  20.476 ms/op
                 listUser·p0.9999: 31.401 ms/op
                 listUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 225312
  mean =      4.264 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2195 
    [ 2.500,  5.000) = 190003 
    [ 5.000,  7.500) = 30538 
    [ 7.500, 10.000) = 1898 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.169 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     16.428 ms/op
     p(99.9900) =     24.983 ms/op
     p(99.9990) =     31.826 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.856 ± 3.089  ops/ms
ClientGrpc.existUser                       thrpt       3  10.315 ± 7.057  ops/ms
ClientGrpc.getUser                         thrpt       3   9.904 ± 2.100  ops/ms
ClientGrpc.listUser                        thrpt       3   7.609 ± 2.350  ops/ms
ClientGrpc.createUser                       avgt       3   3.272 ± 0.986   ms/op
ClientGrpc.existUser                        avgt       3   3.107 ± 0.984   ms/op
ClientGrpc.getUser                          avgt       3   3.231 ± 1.112   ms/op
ClientGrpc.listUser                         avgt       3   4.185 ± 1.267   ms/op
ClientGrpc.createUser                     sample  295679   3.245 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.458           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.203           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.129           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.492           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.414           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.348           ms/op
ClientGrpc.existUser                      sample  306160   3.137 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.798           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.109           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.826           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.047           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.710           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.832           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.100           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.985           ms/op
ClientGrpc.getUser                        sample  292200   3.284 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.653           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.256           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.944           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.145           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.694           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.419           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.712           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.148           ms/op
ClientGrpc.listUser                       sample  225312   4.264 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.882           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.080           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.169           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.643           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.428           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.983           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.883           ms/op
