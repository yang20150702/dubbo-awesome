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
# Warmup Iteration   1: 4.268 ops/ms
# Warmup Iteration   2: 8.894 ops/ms
# Warmup Iteration   3: 9.864 ops/ms
Iteration   1: 10.148 ops/ms
Iteration   2: 10.277 ops/ms
Iteration   3: 10.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.209 ±(99.9%) 1.185 ops/ms [Average]
  (min, avg, max) = (10.148, 10.209, 10.277), stdev = 0.065
  CI (99.9%): [9.024, 11.394] (assumes normal distribution)


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
# Warmup Iteration   1: 7.050 ops/ms
# Warmup Iteration   2: 10.286 ops/ms
# Warmup Iteration   3: 11.007 ops/ms
Iteration   1: 10.833 ops/ms
Iteration   2: 10.707 ops/ms
Iteration   3: 10.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.828 ±(99.9%) 2.158 ops/ms [Average]
  (min, avg, max) = (10.707, 10.828, 10.943), stdev = 0.118
  CI (99.9%): [8.670, 12.985] (assumes normal distribution)


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
# Warmup Iteration   1: 6.885 ops/ms
# Warmup Iteration   2: 10.017 ops/ms
# Warmup Iteration   3: 10.151 ops/ms
Iteration   1: 10.409 ops/ms
Iteration   2: 10.246 ops/ms
Iteration   3: 10.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.301 ±(99.9%) 1.710 ops/ms [Average]
  (min, avg, max) = (10.246, 10.301, 10.409), stdev = 0.094
  CI (99.9%): [8.591, 12.011] (assumes normal distribution)


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
# Warmup Iteration   1: 5.389 ops/ms
# Warmup Iteration   2: 7.944 ops/ms
# Warmup Iteration   3: 8.232 ops/ms
Iteration   1: 8.264 ops/ms
Iteration   2: 8.335 ops/ms
Iteration   3: 8.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.308 ±(99.9%) 0.704 ops/ms [Average]
  (min, avg, max) = (8.264, 8.308, 8.335), stdev = 0.039
  CI (99.9%): [7.604, 9.012] (assumes normal distribution)


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
# Warmup Iteration   1: 4.557 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.003 ms/op
Iteration   1: 3.149 ±(99.9%) 0.004 ms/op
Iteration   2: 3.145 ±(99.9%) 0.004 ms/op
Iteration   3: 3.106 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.133 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (3.106, 3.133, 3.149), stdev = 0.024
  CI (99.9%): [2.694, 3.573] (assumes normal distribution)


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.002 ms/op
Iteration   1: 3.042 ±(99.9%) 0.002 ms/op
Iteration   2: 3.013 ±(99.9%) 0.003 ms/op
Iteration   3: 2.918 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.991 ±(99.9%) 1.182 ms/op [Average]
  (min, avg, max) = (2.918, 2.991, 3.042), stdev = 0.065
  CI (99.9%): [1.809, 4.172] (assumes normal distribution)


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
# Warmup Iteration   1: 4.431 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.004 ms/op
Iteration   1: 3.088 ±(99.9%) 0.004 ms/op
Iteration   2: 3.147 ±(99.9%) 0.002 ms/op
Iteration   3: 3.093 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.109 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (3.088, 3.109, 3.147), stdev = 0.033
  CI (99.9%): [2.513, 3.705] (assumes normal distribution)


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
# Warmup Iteration   1: 5.054 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.014 ms/op
Iteration   1: 3.868 ±(99.9%) 0.020 ms/op
Iteration   2: 3.890 ±(99.9%) 0.035 ms/op
Iteration   3: 3.914 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.891 ±(99.9%) 0.420 ms/op [Average]
  (min, avg, max) = (3.868, 3.891, 3.914), stdev = 0.023
  CI (99.9%): [3.471, 4.311] (assumes normal distribution)


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
# Warmup Iteration   1: 4.429 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
Iteration   1: 3.125 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  10.600 ms/op
                 createUser·p0.9999: 20.242 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   2: 3.066 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.525 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  12.172 ms/op
                 createUser·p0.9999: 34.163 ms/op
                 createUser·p1.00:   35.193 ms/op

Iteration   3: 3.100 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  19.583 ms/op
                 createUser·p0.9999: 25.548 ms/op
                 createUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310390
  mean =      3.097 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14394 
    [ 2.500,  5.000) = 293974 
    [ 5.000,  7.500) = 1444 
    [ 7.500, 10.000) = 194 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =     11.954 ms/op
     p(99.9900) =     27.814 ms/op
     p(99.9990) =     34.734 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 3.785 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
Iteration   1: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.341 ms/op
                 existUser·p0.9999: 17.501 ms/op
                 existUser·p1.00:   17.957 ms/op

Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.476 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  10.196 ms/op
                 existUser·p0.9999: 15.815 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  9.837 ms/op
                 existUser·p0.9999: 15.079 ms/op
                 existUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322958
  mean =      2.973 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1296 
    [ 1.250,  2.500) = 29117 
    [ 2.500,  3.750) = 281886 
    [ 3.750,  5.000) = 8700 
    [ 5.000,  6.250) = 954 
    [ 6.250,  7.500) = 460 
    [ 7.500,  8.750) = 164 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      9.668 ms/op
     p(99.9900) =     16.499 ms/op
     p(99.9990) =     17.884 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.006 ms/op
Iteration   1: 3.194 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.793 ms/op
                 getUser·p0.999:  12.119 ms/op
                 getUser·p0.9999: 15.041 ms/op
                 getUser·p1.00:   16.024 ms/op

Iteration   2: 3.137 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.158 ms/op
                 getUser·p0.9999: 16.115 ms/op
                 getUser·p1.00:   16.400 ms/op

Iteration   3: 3.180 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  13.861 ms/op
                 getUser·p0.9999: 23.655 ms/op
                 getUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302717
  mean =      3.170 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10135 
    [ 2.500,  5.000) = 290573 
    [ 5.000,  7.500) = 1483 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =     11.015 ms/op
     p(99.9900) =     17.808 ms/op
     p(99.9990) =     24.211 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 5.467 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.009 ms/op
Iteration   1: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  13.810 ms/op
                 listUser·p0.9999: 16.069 ms/op
                 listUser·p1.00:   16.564 ms/op

Iteration   2: 3.813 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.125 ms/op
                 listUser·p0.9999: 16.552 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   3: 3.827 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  14.739 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250593
  mean =      3.829 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3440 
    [ 2.500,  5.000) = 232555 
    [ 5.000,  7.500) = 13186 
    [ 7.500, 10.000) = 744 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     17.693 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.209 ± 1.185  ops/ms
ClientGrpc.existUser                       thrpt       3  10.828 ± 2.158  ops/ms
ClientGrpc.getUser                         thrpt       3  10.301 ± 1.710  ops/ms
ClientGrpc.listUser                        thrpt       3   8.308 ± 0.704  ops/ms
ClientGrpc.createUser                       avgt       3   3.133 ± 0.439   ms/op
ClientGrpc.existUser                        avgt       3   2.991 ± 1.182   ms/op
ClientGrpc.getUser                          avgt       3   3.109 ± 0.596   ms/op
ClientGrpc.listUser                         avgt       3   3.891 ± 0.420   ms/op
ClientGrpc.createUser                     sample  310390   3.097 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.525           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.954           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.814           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.193           ms/op
ClientGrpc.existUser                      sample  322958   2.973 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.476           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.668           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.499           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.711           ms/op
ClientGrpc.getUser                        sample  302717   3.170 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.710           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.936           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.015           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.808           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.379           ms/op
ClientGrpc.listUser                       sample  250593   3.829 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.890           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.723           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.358           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.107           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.693           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.152           ms/op
