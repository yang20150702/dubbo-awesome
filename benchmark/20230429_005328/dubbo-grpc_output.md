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
# Warmup Iteration   1: 3.982 ops/ms
# Warmup Iteration   2: 8.593 ops/ms
# Warmup Iteration   3: 9.881 ops/ms
Iteration   1: 10.779 ops/ms
Iteration   2: 11.027 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.850 ±(99.9%) 2.816 ops/ms [Average]
  (min, avg, max) = (10.745, 10.850, 11.027), stdev = 0.154
  CI (99.9%): [8.034, 13.666] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.432 ops/ms
# Warmup Iteration   2: 10.692 ops/ms
# Warmup Iteration   3: 10.999 ops/ms
Iteration   1: 11.139 ops/ms
Iteration   2: 11.366 ops/ms
Iteration   3: 11.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.217 ±(99.9%) 2.351 ops/ms [Average]
  (min, avg, max) = (11.139, 11.217, 11.366), stdev = 0.129
  CI (99.9%): [8.867, 13.568] (assumes normal distribution)


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
# Warmup Iteration   1: 6.614 ops/ms
# Warmup Iteration   2: 10.051 ops/ms
# Warmup Iteration   3: 10.535 ops/ms
Iteration   1: 10.428 ops/ms
Iteration   2: 10.499 ops/ms
Iteration   3: 10.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.446 ±(99.9%) 0.838 ops/ms [Average]
  (min, avg, max) = (10.413, 10.446, 10.499), stdev = 0.046
  CI (99.9%): [9.609, 11.284] (assumes normal distribution)


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
# Warmup Iteration   1: 6.006 ops/ms
# Warmup Iteration   2: 7.287 ops/ms
# Warmup Iteration   3: 7.865 ops/ms
Iteration   1: 7.761 ops/ms
Iteration   2: 7.827 ops/ms
Iteration   3: 7.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.851 ±(99.9%) 1.916 ops/ms [Average]
  (min, avg, max) = (7.761, 7.851, 7.966), stdev = 0.105
  CI (99.9%): [5.936, 9.767] (assumes normal distribution)


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.002 ms/op
Iteration   1: 3.074 ±(99.9%) 0.007 ms/op
Iteration   2: 3.006 ±(99.9%) 0.002 ms/op
Iteration   3: 2.976 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.019 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (2.976, 3.019, 3.074), stdev = 0.050
  CI (99.9%): [2.102, 3.935] (assumes normal distribution)


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
# Warmup Iteration   1: 4.064 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.003 ms/op
Iteration   1: 2.892 ±(99.9%) 0.003 ms/op
Iteration   2: 2.909 ±(99.9%) 0.002 ms/op
Iteration   3: 2.845 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.882 ±(99.9%) 0.607 ms/op [Average]
  (min, avg, max) = (2.845, 2.882, 2.909), stdev = 0.033
  CI (99.9%): [2.275, 3.489] (assumes normal distribution)


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.002 ms/op
Iteration   1: 3.032 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.004 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.016 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (2.992, 3.016, 3.032), stdev = 0.021
  CI (99.9%): [2.633, 3.400] (assumes normal distribution)


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
# Warmup Iteration   1: 5.506 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.009 ms/op
Iteration   1: 3.947 ±(99.9%) 0.026 ms/op
Iteration   2: 3.931 ±(99.9%) 0.005 ms/op
Iteration   3: 3.889 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.922 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (3.889, 3.922, 3.947), stdev = 0.030
  CI (99.9%): [3.371, 4.473] (assumes normal distribution)


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.005 ms/op
Iteration   1: 2.944 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  6.635 ms/op
                 createUser·p0.9999: 12.435 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  9.681 ms/op
                 createUser·p0.9999: 17.770 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.908 ms/op
                 createUser·p0.9999: 16.383 ms/op
                 createUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320975
  mean =      2.987 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 502 
    [ 1.250,  2.500) = 28888 
    [ 2.500,  3.750) = 278712 
    [ 3.750,  5.000) = 11436 
    [ 5.000,  6.250) = 786 
    [ 6.250,  7.500) = 271 
    [ 7.500,  8.750) = 115 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.897 ms/op
     p(99.9900) =     17.426 ms/op
     p(99.9990) =     18.074 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.006 ms/op
Iteration   1: 2.818 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.606 ms/op
                 existUser·p0.9999: 12.948 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   2: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  5.644 ms/op
                 existUser·p0.9999: 13.615 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.835 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.566 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.425 ms/op
                 existUser·p0.9999: 16.833 ms/op
                 existUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336640
  mean =      2.852 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3182 
    [ 1.250,  2.500) = 51241 
    [ 2.500,  3.750) = 272120 
    [ 3.750,  5.000) = 9005 
    [ 5.000,  6.250) = 679 
    [ 6.250,  7.500) = 175 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      6.647 ms/op
     p(99.9900) =     15.663 ms/op
     p(99.9990) =     17.027 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
Iteration   1: 3.031 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.692 ms/op
                 getUser·p0.9999: 14.891 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  6.660 ms/op
                 getUser·p0.9999: 15.044 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   3: 3.018 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.488 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.364 ms/op
                 getUser·p0.9999: 17.773 ms/op
                 getUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317692
  mean =      3.023 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 298 
    [ 1.250,  2.500) = 17349 
    [ 2.500,  3.750) = 286744 
    [ 3.750,  5.000) = 11928 
    [ 5.000,  6.250) = 895 
    [ 6.250,  7.500) = 199 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.080 ms/op
     p(99.9900) =     15.871 ms/op
     p(99.9990) =     18.273 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 5.449 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.012 ms/op
Iteration   1: 3.976 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.917 ms/op
                 listUser·p0.999:  14.017 ms/op
                 listUser·p0.9999: 22.245 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 3.920 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  16.491 ms/op
                 listUser·p0.9999: 21.235 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 3.986 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 17.037 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242447
  mean =      3.960 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2922 
    [ 2.500,  5.000) = 217942 
    [ 5.000,  7.500) = 20413 
    [ 7.500, 10.000) = 724 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     21.357 ms/op
     p(99.9990) =     22.418 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.850 ± 2.816  ops/ms
ClientGrpc.existUser                       thrpt       3  11.217 ± 2.351  ops/ms
ClientGrpc.getUser                         thrpt       3  10.446 ± 0.838  ops/ms
ClientGrpc.listUser                        thrpt       3   7.851 ± 1.916  ops/ms
ClientGrpc.createUser                       avgt       3   3.019 ± 0.916   ms/op
ClientGrpc.existUser                        avgt       3   2.882 ± 0.607   ms/op
ClientGrpc.getUser                          avgt       3   3.016 ± 0.383   ms/op
ClientGrpc.listUser                         avgt       3   3.922 ± 0.551   ms/op
ClientGrpc.createUser                     sample  320975   2.987 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.780           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.897           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.426           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.121           ms/op
ClientGrpc.existUser                      sample  336640   2.852 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.539           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.647           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.663           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.203           ms/op
ClientGrpc.getUser                        sample  317692   3.023 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.488           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.080           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.871           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.383           ms/op
ClientGrpc.listUser                       sample  242447   3.960 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.037           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.483           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.357           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.479           ms/op
