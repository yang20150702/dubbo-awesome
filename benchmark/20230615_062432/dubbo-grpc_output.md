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
# Warmup Iteration   1: 3.780 ops/ms
# Warmup Iteration   2: 8.979 ops/ms
# Warmup Iteration   3: 10.049 ops/ms
Iteration   1: 10.458 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.572 ±(99.9%) 2.382 ops/ms [Average]
  (min, avg, max) = (10.458, 10.572, 10.714), stdev = 0.131
  CI (99.9%): [8.190, 12.954] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.334 ops/ms
# Warmup Iteration   2: 10.483 ops/ms
# Warmup Iteration   3: 11.086 ops/ms
Iteration   1: 11.139 ops/ms
Iteration   2: 11.186 ops/ms
Iteration   3: 11.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.138 ±(99.9%) 0.890 ops/ms [Average]
  (min, avg, max) = (11.088, 11.138, 11.186), stdev = 0.049
  CI (99.9%): [10.248, 12.028] (assumes normal distribution)


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
# Warmup Iteration   1: 7.256 ops/ms
# Warmup Iteration   2: 10.074 ops/ms
# Warmup Iteration   3: 10.466 ops/ms
Iteration   1: 10.592 ops/ms
Iteration   2: 10.473 ops/ms
Iteration   3: 10.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.526 ±(99.9%) 1.105 ops/ms [Average]
  (min, avg, max) = (10.473, 10.526, 10.592), stdev = 0.061
  CI (99.9%): [9.421, 11.631] (assumes normal distribution)


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
# Warmup Iteration   1: 5.763 ops/ms
# Warmup Iteration   2: 7.492 ops/ms
# Warmup Iteration   3: 7.819 ops/ms
Iteration   1: 7.909 ops/ms
Iteration   2: 7.892 ops/ms
Iteration   3: 7.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.926 ±(99.9%) 0.819 ops/ms [Average]
  (min, avg, max) = (7.892, 7.926, 7.977), stdev = 0.045
  CI (99.9%): [7.107, 8.745] (assumes normal distribution)


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.003 ms/op
Iteration   1: 3.045 ±(99.9%) 0.002 ms/op
Iteration   2: 3.072 ±(99.9%) 0.002 ms/op
Iteration   3: 3.016 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.044 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (3.016, 3.044, 3.072), stdev = 0.028
  CI (99.9%): [2.531, 3.557] (assumes normal distribution)


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.001 ms/op
Iteration   1: 2.819 ±(99.9%) 0.004 ms/op
Iteration   2: 2.886 ±(99.9%) 0.003 ms/op
Iteration   3: 2.911 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.872 ±(99.9%) 0.872 ms/op [Average]
  (min, avg, max) = (2.819, 2.872, 2.911), stdev = 0.048
  CI (99.9%): [2.000, 3.744] (assumes normal distribution)


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
# Warmup Iteration   1: 4.240 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.001 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 3.057 ±(99.9%) 0.003 ms/op
Iteration   3: 2.976 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.042 ±(99.9%) 1.086 ms/op [Average]
  (min, avg, max) = (2.976, 3.042, 3.093), stdev = 0.060
  CI (99.9%): [1.956, 4.128] (assumes normal distribution)


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
# Warmup Iteration   1: 4.946 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.031 ms/op
Iteration   1: 4.068 ±(99.9%) 0.014 ms/op
Iteration   2: 4.027 ±(99.9%) 0.036 ms/op
Iteration   3: 3.936 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.011 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (3.936, 4.011, 4.068), stdev = 0.068
  CI (99.9%): [2.775, 5.246] (assumes normal distribution)


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.007 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.654 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.401 ms/op
                 createUser·p0.9999: 18.923 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   2: 3.019 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  5.456 ms/op
                 createUser·p0.9999: 15.244 ms/op
                 createUser·p1.00:   15.434 ms/op

Iteration   3: 3.021 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.719 ms/op
                 createUser·p0.9999: 26.313 ms/op
                 createUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317155
  mean =      3.025 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24939 
    [ 2.500,  5.000) = 290993 
    [ 5.000,  7.500) = 943 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.135 ms/op
     p(99.9900) =     25.732 ms/op
     p(99.9990) =     26.629 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 3.702 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.005 ms/op
Iteration   1: 2.919 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.400 ms/op
                 existUser·p0.999:  6.056 ms/op
                 existUser·p0.9999: 20.089 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   2: 2.945 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.457 ms/op
                 existUser·p0.999:  7.973 ms/op
                 existUser·p0.9999: 14.303 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   3: 2.863 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  6.916 ms/op
                 existUser·p0.9999: 16.897 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330071
  mean =      2.909 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37468 
    [ 2.500,  5.000) = 291507 
    [ 5.000,  7.500) = 798 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.085 ms/op
     p(99.9900) =     17.235 ms/op
     p(99.9990) =     20.405 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 4.357 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
Iteration   1: 3.076 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  12.895 ms/op
                 getUser·p0.9999: 19.091 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  8.273 ms/op
                 getUser·p0.9999: 15.116 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.795 ms/op
                 getUser·p0.9999: 22.654 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315064
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22008 
    [ 2.500,  5.000) = 291366 
    [ 5.000,  7.500) = 1248 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      9.517 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 5.296 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.011 ms/op
Iteration   1: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  13.957 ms/op
                 listUser·p0.9999: 15.777 ms/op
                 listUser·p1.00:   16.040 ms/op

Iteration   2: 4.063 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.116 ms/op
                 listUser·p0.9999: 16.603 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 4.038 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  17.766 ms/op
                 listUser·p0.9999: 27.853 ms/op
                 listUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237995
  mean =      4.031 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1680 
    [ 2.500,  5.000) = 213475 
    [ 5.000,  7.500) = 21374 
    [ 7.500, 10.000) = 1032 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     26.011 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.572 ± 2.382  ops/ms
ClientGrpc.existUser                       thrpt       3  11.138 ± 0.890  ops/ms
ClientGrpc.getUser                         thrpt       3  10.526 ± 1.105  ops/ms
ClientGrpc.listUser                        thrpt       3   7.926 ± 0.819  ops/ms
ClientGrpc.createUser                       avgt       3   3.044 ± 0.513   ms/op
ClientGrpc.existUser                        avgt       3   2.872 ± 0.872   ms/op
ClientGrpc.getUser                          avgt       3   3.042 ± 1.086   ms/op
ClientGrpc.listUser                         avgt       3   4.011 ± 1.236   ms/op
ClientGrpc.createUser                     sample  317155   3.025 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.654           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.135           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.732           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.739           ms/op
ClientGrpc.existUser                      sample  330071   2.909 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.689           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.085           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.235           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.513           ms/op
ClientGrpc.getUser                        sample  315064   3.046 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.618           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.517           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.578           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.970           ms/op
ClientGrpc.listUser                       sample  237995   4.031 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.904           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.155           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.011           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.246           ms/op
