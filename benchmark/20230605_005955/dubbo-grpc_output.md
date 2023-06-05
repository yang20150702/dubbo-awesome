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
# Warmup Iteration   1: 4.156 ops/ms
# Warmup Iteration   2: 9.097 ops/ms
# Warmup Iteration   3: 9.906 ops/ms
Iteration   1: 10.161 ops/ms
Iteration   2: 10.263 ops/ms
Iteration   3: 10.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.248 ±(99.9%) 1.468 ops/ms [Average]
  (min, avg, max) = (10.161, 10.248, 10.320), stdev = 0.080
  CI (99.9%): [8.780, 11.715] (assumes normal distribution)


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
# Warmup Iteration   1: 7.105 ops/ms
# Warmup Iteration   2: 10.208 ops/ms
# Warmup Iteration   3: 10.880 ops/ms
Iteration   1: 10.960 ops/ms
Iteration   2: 10.902 ops/ms
Iteration   3: 10.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.916 ±(99.9%) 0.708 ops/ms [Average]
  (min, avg, max) = (10.886, 10.916, 10.960), stdev = 0.039
  CI (99.9%): [10.208, 11.624] (assumes normal distribution)


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
# Warmup Iteration   1: 7.224 ops/ms
# Warmup Iteration   2: 9.982 ops/ms
# Warmup Iteration   3: 10.312 ops/ms
Iteration   1: 10.195 ops/ms
Iteration   2: 10.153 ops/ms
Iteration   3: 10.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.217 ±(99.9%) 1.415 ops/ms [Average]
  (min, avg, max) = (10.153, 10.217, 10.303), stdev = 0.078
  CI (99.9%): [8.802, 11.633] (assumes normal distribution)


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
# Warmup Iteration   1: 5.394 ops/ms
# Warmup Iteration   2: 7.738 ops/ms
# Warmup Iteration   3: 7.910 ops/ms
Iteration   1: 8.022 ops/ms
Iteration   2: 8.131 ops/ms
Iteration   3: 8.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.064 ±(99.9%) 1.059 ops/ms [Average]
  (min, avg, max) = (8.022, 8.064, 8.131), stdev = 0.058
  CI (99.9%): [7.005, 9.124] (assumes normal distribution)


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
# Warmup Iteration   1: 4.427 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.008 ms/op
Iteration   1: 3.057 ±(99.9%) 0.001 ms/op
Iteration   2: 3.110 ±(99.9%) 0.001 ms/op
Iteration   3: 3.040 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.069 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (3.040, 3.069, 3.110), stdev = 0.037
  CI (99.9%): [2.403, 3.735] (assumes normal distribution)


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.002 ms/op
Iteration   1: 2.962 ±(99.9%) 0.002 ms/op
Iteration   2: 2.967 ±(99.9%) 0.002 ms/op
Iteration   3: 2.962 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.964 ±(99.9%) 0.057 ms/op [Average]
  (min, avg, max) = (2.962, 2.964, 2.967), stdev = 0.003
  CI (99.9%): [2.906, 3.021] (assumes normal distribution)


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
# Warmup Iteration   1: 4.135 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.003 ms/op
Iteration   2: 3.064 ±(99.9%) 0.004 ms/op
Iteration   3: 3.057 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.059 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (3.057, 3.059, 3.064), stdev = 0.004
  CI (99.9%): [2.982, 3.137] (assumes normal distribution)


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
# Warmup Iteration   1: 5.360 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.017 ms/op
Iteration   1: 3.940 ±(99.9%) 0.013 ms/op
Iteration   2: 3.914 ±(99.9%) 0.014 ms/op
Iteration   3: 4.059 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.971 ±(99.9%) 1.407 ms/op [Average]
  (min, avg, max) = (3.914, 3.971, 4.059), stdev = 0.077
  CI (99.9%): [2.564, 5.378] (assumes normal distribution)


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
Iteration   1: 3.046 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 17.170 ms/op
                 createUser·p1.00:   17.596 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  7.554 ms/op
                 createUser·p0.9999: 19.927 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.424 ms/op
                 createUser·p0.9999: 20.889 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314677
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21209 
    [ 2.500,  5.000) = 291670 
    [ 5.000,  7.500) = 1345 
    [ 7.500, 10.000) = 225 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     21.065 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.006 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  9.357 ms/op
                 existUser·p0.9999: 19.120 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   2: 3.019 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  8.167 ms/op
                 existUser·p0.9999: 14.939 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   3: 2.913 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.293 ms/op
                 existUser·p0.9999: 17.433 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323287
  mean =      2.969 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 406 
    [ 1.250,  2.500) = 30893 
    [ 2.500,  3.750) = 279601 
    [ 3.750,  5.000) = 10947 
    [ 5.000,  6.250) = 603 
    [ 6.250,  7.500) = 388 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      8.187 ms/op
     p(99.9900) =     18.221 ms/op
     p(99.9990) =     19.507 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 4.350 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.006 ms/op
Iteration   1: 3.070 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.522 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  7.447 ms/op
                 getUser·p0.9999: 13.217 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.004 ms/op
                 getUser·p0.9999: 15.375 ms/op
                 getUser·p1.00:   17.400 ms/op

Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.221 ms/op
                 getUser·p0.9999: 16.969 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313969
  mean =      3.058 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 863 
    [ 1.250,  2.500) = 16822 
    [ 2.500,  3.750) = 277339 
    [ 3.750,  5.000) = 17106 
    [ 5.000,  6.250) = 1195 
    [ 6.250,  7.500) = 388 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      7.250 ms/op
     p(99.9900) =     16.092 ms/op
     p(99.9990) =     17.648 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 4.715 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.175 ±(99.9%) 0.014 ms/op
Iteration   1: 3.972 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 19.495 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 3.947 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   7.042 ms/op
                 listUser·p0.999:  19.067 ms/op
                 listUser·p0.9999: 27.066 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   3: 3.961 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 23.621 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242329
  mean =      3.960 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1571 
    [ 2.500,  5.000) = 221131 
    [ 5.000,  7.500) = 18125 
    [ 7.500, 10.000) = 1029 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     16.444 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     28.485 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.248 ± 1.468  ops/ms
ClientGrpc.existUser                       thrpt       3  10.916 ± 0.708  ops/ms
ClientGrpc.getUser                         thrpt       3  10.217 ± 1.415  ops/ms
ClientGrpc.listUser                        thrpt       3   8.064 ± 1.059  ops/ms
ClientGrpc.createUser                       avgt       3   3.069 ± 0.666   ms/op
ClientGrpc.existUser                        avgt       3   2.964 ± 0.057   ms/op
ClientGrpc.getUser                          avgt       3   3.059 ± 0.077   ms/op
ClientGrpc.listUser                         avgt       3   3.971 ± 1.407   ms/op
ClientGrpc.createUser                     sample  314677   3.051 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.738           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.487           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.644           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.365           ms/op
ClientGrpc.existUser                      sample  323287   2.969 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.774           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.187           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.221           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.628           ms/op
ClientGrpc.getUser                        sample  313969   3.058 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.522           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.250           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.092           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.662           ms/op
ClientGrpc.listUser                       sample  242329   3.960 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.992           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.444           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.870           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.574           ms/op
