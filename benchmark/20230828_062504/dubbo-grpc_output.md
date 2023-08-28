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
# Warmup Iteration   1: 4.499 ops/ms
# Warmup Iteration   2: 9.178 ops/ms
# Warmup Iteration   3: 10.178 ops/ms
Iteration   1: 10.551 ops/ms
Iteration   2: 10.640 ops/ms
Iteration   3: 10.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.531 ±(99.9%) 2.210 ops/ms [Average]
  (min, avg, max) = (10.400, 10.531, 10.640), stdev = 0.121
  CI (99.9%): [8.321, 12.741] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.584 ops/ms
# Warmup Iteration   2: 10.810 ops/ms
# Warmup Iteration   3: 11.324 ops/ms
Iteration   1: 11.013 ops/ms
Iteration   2: 11.362 ops/ms
Iteration   3: 11.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.191 ±(99.9%) 3.184 ops/ms [Average]
  (min, avg, max) = (11.013, 11.191, 11.362), stdev = 0.175
  CI (99.9%): [8.007, 14.375] (assumes normal distribution)


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
# Warmup Iteration   1: 7.767 ops/ms
# Warmup Iteration   2: 10.346 ops/ms
# Warmup Iteration   3: 10.427 ops/ms
Iteration   1: 10.515 ops/ms
Iteration   2: 10.508 ops/ms
Iteration   3: 10.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.535 ±(99.9%) 0.750 ops/ms [Average]
  (min, avg, max) = (10.508, 10.535, 10.583), stdev = 0.041
  CI (99.9%): [9.785, 11.286] (assumes normal distribution)


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
# Warmup Iteration   1: 6.840 ops/ms
# Warmup Iteration   2: 7.827 ops/ms
# Warmup Iteration   3: 8.148 ops/ms
Iteration   1: 8.042 ops/ms
Iteration   2: 8.171 ops/ms
Iteration   3: 8.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.110 ±(99.9%) 1.186 ops/ms [Average]
  (min, avg, max) = (8.042, 8.110, 8.171), stdev = 0.065
  CI (99.9%): [6.924, 9.296] (assumes normal distribution)


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.036 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
Iteration   3: 3.002 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.022 ±(99.9%) 0.325 ms/op [Average]
  (min, avg, max) = (3.002, 3.022, 3.036), stdev = 0.018
  CI (99.9%): [2.697, 3.347] (assumes normal distribution)


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.870 ±(99.9%) 0.004 ms/op
Iteration   1: 2.876 ±(99.9%) 0.003 ms/op
Iteration   2: 2.867 ±(99.9%) 0.003 ms/op
Iteration   3: 2.859 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.867 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (2.859, 2.867, 2.876), stdev = 0.009
  CI (99.9%): [2.711, 3.024] (assumes normal distribution)


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.002 ms/op
Iteration   1: 3.044 ±(99.9%) 0.002 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 3.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.015 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (2.985, 3.015, 3.044), stdev = 0.030
  CI (99.9%): [2.475, 3.554] (assumes normal distribution)


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
# Warmup Iteration   1: 5.058 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.013 ms/op
Iteration   1: 3.974 ±(99.9%) 0.007 ms/op
Iteration   2: 3.905 ±(99.9%) 0.008 ms/op
Iteration   3: 3.971 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.950 ±(99.9%) 0.711 ms/op [Average]
  (min, avg, max) = (3.905, 3.950, 3.974), stdev = 0.039
  CI (99.9%): [3.239, 4.661] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.790 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.007 ms/op
Iteration   1: 3.011 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.512 ms/op
                 createUser·p0.999:  8.434 ms/op
                 createUser·p0.9999: 22.000 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  8.633 ms/op
                 createUser·p0.9999: 16.384 ms/op
                 createUser·p1.00:   18.219 ms/op

Iteration   3: 3.093 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.079 ms/op
                 createUser·p0.999:  9.736 ms/op
                 createUser·p0.9999: 19.344 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316696
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26310 
    [ 2.500,  5.000) = 287985 
    [ 5.000,  7.500) = 1860 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.008 ms/op
Iteration   1: 2.877 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  7.945 ms/op
                 existUser·p0.9999: 19.755 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   2: 2.876 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  6.939 ms/op
                 existUser·p0.9999: 14.352 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   3: 2.914 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  7.107 ms/op
                 existUser·p0.9999: 18.285 ms/op
                 existUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331967
  mean =      2.889 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47555 
    [ 2.500,  5.000) = 281982 
    [ 5.000,  7.500) = 2126 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.680 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     18.403 ms/op
     p(99.9990) =     19.945 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
Iteration   1: 3.047 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  8.403 ms/op
                 getUser·p0.9999: 15.466 ms/op
                 getUser·p1.00:   15.860 ms/op

Iteration   2: 3.135 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.980 ms/op
                 getUser·p0.99:   5.071 ms/op
                 getUser·p0.999:  9.253 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.552 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  7.977 ms/op
                 getUser·p0.9999: 23.069 ms/op
                 getUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312330
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22765 
    [ 2.500,  5.000) = 286684 
    [ 5.000,  7.500) = 2326 
    [ 7.500, 10.000) = 298 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.891 ms/op
     p(99.9000) =      8.629 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 5.291 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.012 ms/op
Iteration   1: 3.951 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  13.567 ms/op
                 listUser·p0.9999: 15.383 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   2: 3.995 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.461 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  18.906 ms/op
                 listUser·p0.9999: 26.018 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   3: 3.920 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.763 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.047 ms/op
                 listUser·p0.999:  16.037 ms/op
                 listUser·p0.9999: 21.922 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242603
  mean =      3.955 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5073 
    [ 2.500,  5.000) = 213580 
    [ 5.000,  7.500) = 21950 
    [ 7.500, 10.000) = 1404 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     24.961 ms/op
     p(99.9990) =     26.421 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.531 ± 2.210  ops/ms
ClientGrpc.existUser                       thrpt       3  11.191 ± 3.184  ops/ms
ClientGrpc.getUser                         thrpt       3  10.535 ± 0.750  ops/ms
ClientGrpc.listUser                        thrpt       3   8.110 ± 1.186  ops/ms
ClientGrpc.createUser                       avgt       3   3.022 ± 0.325   ms/op
ClientGrpc.existUser                        avgt       3   2.867 ± 0.156   ms/op
ClientGrpc.getUser                          avgt       3   3.015 ± 0.539   ms/op
ClientGrpc.listUser                         avgt       3   3.950 ± 0.711   ms/op
ClientGrpc.createUser                     sample  316696   3.031 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.572           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.751           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.535           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.496           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.249           ms/op
ClientGrpc.existUser                      sample  331967   2.889 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.539           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.680           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.389           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.403           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.021           ms/op
ClientGrpc.getUser                        sample  312330   3.073 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.609           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.891           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.629           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.283           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.167           ms/op
ClientGrpc.listUser                       sample  242603   3.955 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.461           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.307           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.827           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.961           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.804           ms/op
