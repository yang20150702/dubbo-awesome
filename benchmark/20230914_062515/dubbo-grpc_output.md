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
# Warmup Iteration   1: 3.964 ops/ms
# Warmup Iteration   2: 8.226 ops/ms
# Warmup Iteration   3: 9.831 ops/ms
Iteration   1: 10.083 ops/ms
Iteration   2: 10.304 ops/ms
Iteration   3: 10.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.150 ±(99.9%) 2.433 ops/ms [Average]
  (min, avg, max) = (10.064, 10.150, 10.304), stdev = 0.133
  CI (99.9%): [7.718, 12.583] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.198 ops/ms
# Warmup Iteration   2: 10.410 ops/ms
# Warmup Iteration   3: 10.998 ops/ms
Iteration   1: 10.843 ops/ms
Iteration   2: 10.885 ops/ms
Iteration   3: 10.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.861 ±(99.9%) 0.398 ops/ms [Average]
  (min, avg, max) = (10.843, 10.861, 10.885), stdev = 0.022
  CI (99.9%): [10.462, 11.259] (assumes normal distribution)


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
# Warmup Iteration   1: 7.275 ops/ms
# Warmup Iteration   2: 9.965 ops/ms
# Warmup Iteration   3: 10.241 ops/ms
Iteration   1: 10.367 ops/ms
Iteration   2: 10.370 ops/ms
Iteration   3: 10.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.347 ±(99.9%) 0.683 ops/ms [Average]
  (min, avg, max) = (10.304, 10.347, 10.370), stdev = 0.037
  CI (99.9%): [9.664, 11.030] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.837 ops/ms
# Warmup Iteration   2: 7.870 ops/ms
# Warmup Iteration   3: 8.105 ops/ms
Iteration   1: 8.282 ops/ms
Iteration   2: 8.162 ops/ms
Iteration   3: 8.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.316 ±(99.9%) 3.162 ops/ms [Average]
  (min, avg, max) = (8.162, 8.316, 8.503), stdev = 0.173
  CI (99.9%): [5.153, 11.478] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.342 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.001 ms/op
Iteration   1: 3.146 ±(99.9%) 0.002 ms/op
Iteration   2: 3.104 ±(99.9%) 0.002 ms/op
Iteration   3: 3.103 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.118 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (3.103, 3.118, 3.146), stdev = 0.025
  CI (99.9%): [2.666, 3.569] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.616 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.001 ms/op
Iteration   1: 2.920 ±(99.9%) 0.003 ms/op
Iteration   2: 2.992 ±(99.9%) 0.002 ms/op
Iteration   3: 3.020 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.977 ±(99.9%) 0.938 ms/op [Average]
  (min, avg, max) = (2.920, 2.977, 3.020), stdev = 0.051
  CI (99.9%): [2.039, 3.915] (assumes normal distribution)


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.002 ms/op
Iteration   2: 3.093 ±(99.9%) 0.003 ms/op
Iteration   3: 3.123 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.105 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (3.093, 3.105, 3.123), stdev = 0.016
  CI (99.9%): [2.814, 3.395] (assumes normal distribution)


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
# Warmup Iteration   1: 5.634 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.038 ms/op
Iteration   1: 3.880 ±(99.9%) 0.024 ms/op
Iteration   2: 3.908 ±(99.9%) 0.020 ms/op
Iteration   3: 3.941 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.910 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (3.880, 3.910, 3.941), stdev = 0.030
  CI (99.9%): [3.358, 4.462] (assumes normal distribution)


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
# Warmup Iteration   1: 4.628 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.006 ms/op
Iteration   1: 3.111 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.866 ms/op
                 createUser·p0.999:  8.202 ms/op
                 createUser·p0.9999: 18.973 ms/op
                 createUser·p1.00:   20.087 ms/op

Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.910 ms/op
                 createUser·p0.999:  11.484 ms/op
                 createUser·p0.9999: 17.891 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.750 ms/op
                 createUser·p0.999:  9.245 ms/op
                 createUser·p0.9999: 21.124 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308585
  mean =      3.112 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15972 
    [ 2.500,  5.000) = 289932 
    [ 5.000,  7.500) = 2146 
    [ 7.500, 10.000) = 271 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     19.534 ms/op
     p(99.9990) =     21.946 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.014 ms/op
                 existUser·p0.999:  7.291 ms/op
                 existUser·p0.9999: 13.861 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.389 ms/op
                 existUser·p0.9999: 13.367 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  10.616 ms/op
                 existUser·p0.9999: 17.316 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318644
  mean =      3.011 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 804 
    [ 1.250,  2.500) = 28211 
    [ 2.500,  3.750) = 276398 
    [ 3.750,  5.000) = 11616 
    [ 5.000,  6.250) = 801 
    [ 6.250,  7.500) = 428 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      9.040 ms/op
     p(99.9900) =     16.091 ms/op
     p(99.9990) =     17.689 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.615 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.293 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
Iteration   1: 3.115 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  8.536 ms/op
                 getUser·p0.9999: 12.951 ms/op
                 getUser·p1.00:   13.255 ms/op

Iteration   2: 3.126 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  8.208 ms/op
                 getUser·p0.9999: 14.796 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.772 ms/op
                 getUser·p0.9999: 17.143 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309339
  mean =      3.104 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 333 
    [ 1.250,  2.500) = 12322 
    [ 2.500,  3.750) = 278270 
    [ 3.750,  5.000) = 15969 
    [ 5.000,  6.250) = 1360 
    [ 6.250,  7.500) = 622 
    [ 7.500,  8.750) = 233 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 84 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      8.296 ms/op
     p(99.9900) =     15.544 ms/op
     p(99.9990) =     17.528 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 5.023 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.009 ms/op
Iteration   1: 3.960 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.628 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.796 ms/op
                 listUser·p0.9999: 14.479 ms/op
                 listUser·p1.00:   15.352 ms/op

Iteration   2: 3.902 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.676 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 16.030 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 18.901 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243783
  mean =      3.939 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 2543 
    [ 2.500,  3.750) = 97453 
    [ 3.750,  5.000) = 128924 
    [ 5.000,  6.250) = 9336 
    [ 6.250,  7.500) = 4247 
    [ 7.500,  8.750) = 550 
    [ 8.750, 10.000) = 182 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 154 
    [15.000, 16.250) = 61 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     14.094 ms/op
     p(99.9900) =     17.374 ms/op
     p(99.9990) =     19.458 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.150 ± 2.433  ops/ms
ClientGrpc.existUser                       thrpt       3  10.861 ± 0.398  ops/ms
ClientGrpc.getUser                         thrpt       3  10.347 ± 0.683  ops/ms
ClientGrpc.listUser                        thrpt       3   8.316 ± 3.162  ops/ms
ClientGrpc.createUser                       avgt       3   3.118 ± 0.452   ms/op
ClientGrpc.existUser                        avgt       3   2.977 ± 0.938   ms/op
ClientGrpc.getUser                          avgt       3   3.105 ± 0.291   ms/op
ClientGrpc.listUser                         avgt       3   3.910 ± 0.552   ms/op
ClientGrpc.createUser                     sample  308585   3.112 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.593           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.850           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.257           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.534           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.217           ms/op
ClientGrpc.existUser                      sample  318644   3.011 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.680           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.040           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.091           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.859           ms/op
ClientGrpc.getUser                        sample  309339   3.104 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.752           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.296           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.544           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.662           ms/op
ClientGrpc.listUser                       sample  243783   3.939 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.676           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.094           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.374           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.562           ms/op
