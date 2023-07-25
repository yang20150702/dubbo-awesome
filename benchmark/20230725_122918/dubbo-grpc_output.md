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
# Warmup Iteration   1: 3.218 ops/ms
# Warmup Iteration   2: 7.451 ops/ms
# Warmup Iteration   3: 9.091 ops/ms
Iteration   1: 9.726 ops/ms
Iteration   2: 9.748 ops/ms
Iteration   3: 9.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.712 ±(99.9%) 0.803 ops/ms [Average]
  (min, avg, max) = (9.663, 9.712, 9.748), stdev = 0.044
  CI (99.9%): [8.909, 10.516] (assumes normal distribution)


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
# Warmup Iteration   1: 6.033 ops/ms
# Warmup Iteration   2: 9.606 ops/ms
# Warmup Iteration   3: 10.116 ops/ms
Iteration   1: 10.482 ops/ms
Iteration   2: 10.497 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.479 ±(99.9%) 0.361 ops/ms [Average]
  (min, avg, max) = (10.458, 10.479, 10.497), stdev = 0.020
  CI (99.9%): [10.118, 10.840] (assumes normal distribution)


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
# Warmup Iteration   1: 5.724 ops/ms
# Warmup Iteration   2: 8.987 ops/ms
# Warmup Iteration   3: 9.685 ops/ms
Iteration   1: 9.660 ops/ms
Iteration   2: 9.783 ops/ms
Iteration   3: 9.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.802 ±(99.9%) 2.776 ops/ms [Average]
  (min, avg, max) = (9.660, 9.802, 9.963), stdev = 0.152
  CI (99.9%): [7.026, 12.578] (assumes normal distribution)


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
# Warmup Iteration   1: 4.918 ops/ms
# Warmup Iteration   2: 6.491 ops/ms
# Warmup Iteration   3: 7.256 ops/ms
Iteration   1: 7.323 ops/ms
Iteration   2: 7.539 ops/ms
Iteration   3: 7.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.404 ±(99.9%) 2.144 ops/ms [Average]
  (min, avg, max) = (7.323, 7.404, 7.539), stdev = 0.117
  CI (99.9%): [5.260, 9.548] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.362 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.002 ms/op
Iteration   1: 3.218 ±(99.9%) 0.002 ms/op
Iteration   2: 3.222 ±(99.9%) 0.003 ms/op
Iteration   3: 3.193 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.211 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (3.193, 3.211, 3.222), stdev = 0.015
  CI (99.9%): [2.929, 3.493] (assumes normal distribution)


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
# Warmup Iteration   1: 4.714 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.002 ms/op
Iteration   1: 3.040 ±(99.9%) 0.003 ms/op
Iteration   2: 3.095 ±(99.9%) 0.002 ms/op
Iteration   3: 3.085 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.073 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.040, 3.073, 3.095), stdev = 0.029
  CI (99.9%): [2.536, 3.610] (assumes normal distribution)


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
# Warmup Iteration   1: 5.022 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.430 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.003 ms/op
Iteration   1: 3.283 ±(99.9%) 0.003 ms/op
Iteration   2: 3.232 ±(99.9%) 0.001 ms/op
Iteration   3: 3.198 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.238 ±(99.9%) 0.779 ms/op [Average]
  (min, avg, max) = (3.198, 3.238, 3.283), stdev = 0.043
  CI (99.9%): [2.459, 4.017] (assumes normal distribution)


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
# Warmup Iteration   1: 5.688 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.510 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.035 ms/op
Iteration   1: 4.131 ±(99.9%) 0.009 ms/op
Iteration   2: 4.258 ±(99.9%) 0.013 ms/op
Iteration   3: 4.195 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.194 ±(99.9%) 1.159 ms/op [Average]
  (min, avg, max) = (4.131, 4.194, 4.258), stdev = 0.064
  CI (99.9%): [3.036, 5.353] (assumes normal distribution)


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
# Warmup Iteration   1: 4.735 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.007 ms/op
Iteration   1: 3.196 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.803 ms/op
                 createUser·p0.999:  7.946 ms/op
                 createUser·p0.9999: 13.893 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 18.860 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   3: 3.133 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  14.500 ms/op
                 createUser·p0.9999: 22.143 ms/op
                 createUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304647
  mean =      3.153 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13793 
    [ 2.500,  5.000) = 288857 
    [ 5.000,  7.500) = 1360 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     21.612 ms/op
     p(99.9990) =     22.379 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 4.430 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
Iteration   1: 3.122 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.576 ms/op
                 existUser·p0.9999: 15.229 ms/op
                 existUser·p1.00:   15.843 ms/op

Iteration   2: 3.122 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.981 ms/op
                 existUser·p0.999:  11.649 ms/op
                 existUser·p0.9999: 16.003 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  8.222 ms/op
                 existUser·p0.9999: 32.408 ms/op
                 existUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 306108
  mean =      3.135 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11079 
    [ 2.500,  5.000) = 292843 
    [ 5.000,  7.500) = 1615 
    [ 7.500, 10.000) = 290 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      9.059 ms/op
     p(99.9900) =     31.568 ms/op
     p(99.9990) =     32.473 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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
# Warmup Iteration   1: 4.765 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.007 ms/op
Iteration   1: 3.179 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.735 ms/op
                 getUser·p0.9999: 17.924 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 3.172 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.708 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.677 ms/op
                 getUser·p0.9999: 19.721 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   3: 3.261 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.117 ms/op
                 getUser·p0.9999: 22.125 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299525
  mean =      3.203 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9597 
    [ 2.500,  5.000) = 288299 
    [ 5.000,  7.500) = 1241 
    [ 7.500, 10.000) = 228 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.844 ms/op
     p(99.9900) =     21.366 ms/op
     p(99.9990) =     23.529 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 5.288 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.383 ±(99.9%) 0.013 ms/op
Iteration   1: 4.221 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.866 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  16.695 ms/op
                 listUser·p0.9999: 21.228 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   2: 4.236 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  16.679 ms/op
                 listUser·p0.9999: 19.854 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 4.228 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.093 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 29.224 ms/op
                 listUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 227146
  mean =      4.228 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 874 
    [ 2.500,  5.000) = 197682 
    [ 5.000,  7.500) = 26129 
    [ 7.500, 10.000) = 1848 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     26.776 ms/op
     p(99.9990) =     29.643 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.712 ± 0.803  ops/ms
ClientGrpc.existUser                       thrpt       3  10.479 ± 0.361  ops/ms
ClientGrpc.getUser                         thrpt       3   9.802 ± 2.776  ops/ms
ClientGrpc.listUser                        thrpt       3   7.404 ± 2.144  ops/ms
ClientGrpc.createUser                       avgt       3   3.211 ± 0.282   ms/op
ClientGrpc.existUser                        avgt       3   3.073 ± 0.537   ms/op
ClientGrpc.getUser                          avgt       3   3.238 ± 0.779   ms/op
ClientGrpc.listUser                         avgt       3   4.194 ± 1.159   ms/op
ClientGrpc.createUser                     sample  304647   3.153 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.787           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.372           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.612           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.479           ms/op
ClientGrpc.existUser                      sample  306108   3.135 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.765           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.101           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.645           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.059           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.568           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.473           ms/op
ClientGrpc.getUser                        sample  299525   3.203 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.888           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.170           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.844           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.366           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.921           ms/op
ClientGrpc.listUser                       sample  227146   4.228 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.409           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.035           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.095           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.569           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.088           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.776           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.753           ms/op
