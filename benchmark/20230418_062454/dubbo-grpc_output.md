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
# Warmup Iteration   1: 4.314 ops/ms
# Warmup Iteration   2: 9.354 ops/ms
# Warmup Iteration   3: 10.223 ops/ms
Iteration   1: 10.350 ops/ms
Iteration   2: 10.430 ops/ms
Iteration   3: 10.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.378 ±(99.9%) 0.816 ops/ms [Average]
  (min, avg, max) = (10.350, 10.378, 10.430), stdev = 0.045
  CI (99.9%): [9.562, 11.194] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.332 ops/ms
# Warmup Iteration   2: 10.524 ops/ms
# Warmup Iteration   3: 11.087 ops/ms
Iteration   1: 11.160 ops/ms
Iteration   2: 10.972 ops/ms
Iteration   3: 10.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.040 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (10.972, 11.040, 11.160), stdev = 0.104
  CI (99.9%): [9.145, 12.936] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.993 ops/ms
# Warmup Iteration   2: 9.844 ops/ms
# Warmup Iteration   3: 10.239 ops/ms
Iteration   1: 10.321 ops/ms
Iteration   2: 10.514 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.425 ±(99.9%) 1.781 ops/ms [Average]
  (min, avg, max) = (10.321, 10.425, 10.514), stdev = 0.098
  CI (99.9%): [8.644, 12.207] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.827 ops/ms
# Warmup Iteration   2: 7.706 ops/ms
# Warmup Iteration   3: 8.066 ops/ms
Iteration   1: 8.085 ops/ms
Iteration   2: 8.307 ops/ms
Iteration   3: 8.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.171 ±(99.9%) 2.172 ops/ms [Average]
  (min, avg, max) = (8.085, 8.171, 8.307), stdev = 0.119
  CI (99.9%): [5.999, 10.343] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.304 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.004 ms/op
Iteration   1: 3.024 ±(99.9%) 0.004 ms/op
Iteration   2: 3.063 ±(99.9%) 0.003 ms/op
Iteration   3: 2.976 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.021 ±(99.9%) 0.795 ms/op [Average]
  (min, avg, max) = (2.976, 3.021, 3.063), stdev = 0.044
  CI (99.9%): [2.226, 3.816] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.004 ms/op
Iteration   1: 2.955 ±(99.9%) 0.002 ms/op
Iteration   2: 2.927 ±(99.9%) 0.003 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.963 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (2.927, 2.963, 3.008), stdev = 0.041
  CI (99.9%): [2.213, 3.714] (assumes normal distribution)


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
# Warmup Iteration   1: 4.290 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.003 ms/op
Iteration   1: 3.790 ±(99.9%) 0.001 ms/op
Iteration   2: 3.088 ±(99.9%) 0.003 ms/op
Iteration   3: 2.977 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.285 ±(99.9%) 8.039 ms/op [Average]
  (min, avg, max) = (2.977, 3.285, 3.790), stdev = 0.441
  CI (99.9%): [≈ 0, 11.324] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.301 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.015 ms/op
Iteration   1: 3.897 ±(99.9%) 0.028 ms/op
Iteration   2: 3.833 ±(99.9%) 0.006 ms/op
Iteration   3: 3.925 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.885 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (3.833, 3.885, 3.925), stdev = 0.047
  CI (99.9%): [3.029, 4.741] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.080 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  7.974 ms/op
                 createUser·p0.9999: 16.093 ms/op
                 createUser·p1.00:   16.466 ms/op

Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  6.989 ms/op
                 createUser·p0.9999: 23.680 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  10.208 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311393
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23385 
    [ 2.500,  5.000) = 286379 
    [ 5.000,  7.500) = 1259 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      8.035 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     23.979 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.031 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
Iteration   1: 2.936 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.063 ms/op
                 existUser·p0.9999: 12.146 ms/op
                 existUser·p1.00:   12.665 ms/op

Iteration   2: 2.926 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  6.156 ms/op
                 existUser·p0.9999: 14.026 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   3: 2.908 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.492 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.118 ms/op
                 existUser·p0.999:  9.357 ms/op
                 existUser·p0.9999: 17.597 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328195
  mean =      2.923 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 722 
    [ 1.250,  2.500) = 36740 
    [ 2.500,  3.750) = 280658 
    [ 3.750,  5.000) = 9325 
    [ 5.000,  6.250) = 360 
    [ 6.250,  7.500) = 189 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      6.439 ms/op
     p(99.9900) =     16.239 ms/op
     p(99.9990) =     17.873 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.004 ms/op
                 getUser·p0.9999: 19.347 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  6.535 ms/op
                 getUser·p0.9999: 15.033 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  6.361 ms/op
                 getUser·p0.9999: 23.834 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316399
  mean =      3.035 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21821 
    [ 2.500,  5.000) = 293102 
    [ 5.000,  7.500) = 1266 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      6.717 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     24.014 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 4.582 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.012 ms/op
Iteration   1: 3.951 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.573 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  14.138 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 3.958 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  18.335 ms/op
                 listUser·p0.9999: 27.820 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   3: 3.952 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.023 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 27.126 ms/op
                 listUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242877
  mean =      3.954 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4184 
    [ 2.500,  5.000) = 213401 
    [ 5.000,  7.500) = 24051 
    [ 7.500, 10.000) = 778 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     27.286 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.378 ± 0.816  ops/ms
ClientGrpc.existUser                       thrpt       3  11.040 ± 1.896  ops/ms
ClientGrpc.getUser                         thrpt       3  10.425 ± 1.781  ops/ms
ClientGrpc.listUser                        thrpt       3   8.171 ± 2.172  ops/ms
ClientGrpc.createUser                       avgt       3   3.021 ± 0.795   ms/op
ClientGrpc.existUser                        avgt       3   2.963 ± 0.750   ms/op
ClientGrpc.getUser                          avgt       3   3.285 ± 8.039   ms/op
ClientGrpc.listUser                         avgt       3   3.885 ± 0.856   ms/op
ClientGrpc.createUser                     sample  311393   3.084 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.603           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.035           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.839           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.445           ms/op
ClientGrpc.existUser                      sample  328195   2.923 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.492           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.439           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.239           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  316399   3.035 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.689           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.717           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.151           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.216           ms/op
ClientGrpc.listUser                       sample  242877   3.954 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.573           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.286           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.984           ms/op
