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
# Warmup Iteration   1: 3.887 ops/ms
# Warmup Iteration   2: 8.462 ops/ms
# Warmup Iteration   3: 9.640 ops/ms
Iteration   1: 9.780 ops/ms
Iteration   2: 9.795 ops/ms
Iteration   3: 10.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.887 ±(99.9%) 3.169 ops/ms [Average]
  (min, avg, max) = (9.780, 9.887, 10.088), stdev = 0.174
  CI (99.9%): [6.718, 13.057] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 7.041 ops/ms
# Warmup Iteration   2: 9.862 ops/ms
# Warmup Iteration   3: 10.232 ops/ms
Iteration   1: 10.490 ops/ms
Iteration   2: 10.294 ops/ms
Iteration   3: 10.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.432 ±(99.9%) 2.203 ops/ms [Average]
  (min, avg, max) = (10.294, 10.432, 10.513), stdev = 0.121
  CI (99.9%): [8.229, 12.636] (assumes normal distribution)


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
# Warmup Iteration   1: 6.628 ops/ms
# Warmup Iteration   2: 9.729 ops/ms
# Warmup Iteration   3: 10.139 ops/ms
Iteration   1: 10.087 ops/ms
Iteration   2: 10.010 ops/ms
Iteration   3: 10.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.074 ±(99.9%) 1.069 ops/ms [Average]
  (min, avg, max) = (10.010, 10.074, 10.125), stdev = 0.059
  CI (99.9%): [9.006, 11.143] (assumes normal distribution)


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
# Warmup Iteration   1: 5.727 ops/ms
# Warmup Iteration   2: 7.623 ops/ms
# Warmup Iteration   3: 7.924 ops/ms
Iteration   1: 8.287 ops/ms
Iteration   2: 7.963 ops/ms
Iteration   3: 8.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.090 ±(99.9%) 3.165 ops/ms [Average]
  (min, avg, max) = (7.963, 8.090, 8.287), stdev = 0.173
  CI (99.9%): [4.925, 11.254] (assumes normal distribution)


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
# Warmup Iteration   1: 4.773 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.003 ms/op
Iteration   1: 3.225 ±(99.9%) 0.005 ms/op
Iteration   2: 3.255 ±(99.9%) 0.003 ms/op
Iteration   3: 3.206 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.229 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (3.206, 3.229, 3.255), stdev = 0.025
  CI (99.9%): [2.778, 3.680] (assumes normal distribution)


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.046 ±(99.9%) 0.003 ms/op
Iteration   2: 3.094 ±(99.9%) 0.004 ms/op
Iteration   3: 3.056 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.065 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (3.046, 3.065, 3.094), stdev = 0.025
  CI (99.9%): [2.603, 3.528] (assumes normal distribution)


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
# Warmup Iteration   1: 4.545 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.002 ms/op
Iteration   1: 3.192 ±(99.9%) 0.004 ms/op
Iteration   2: 3.246 ±(99.9%) 0.003 ms/op
Iteration   3: 3.121 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.186 ±(99.9%) 1.148 ms/op [Average]
  (min, avg, max) = (3.121, 3.186, 3.246), stdev = 0.063
  CI (99.9%): [2.038, 4.334] (assumes normal distribution)


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
# Warmup Iteration   1: 5.829 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.010 ms/op
Iteration   1: 4.121 ±(99.9%) 0.013 ms/op
Iteration   2: 4.134 ±(99.9%) 0.015 ms/op
Iteration   3: 4.044 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.099 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (4.044, 4.099, 4.134), stdev = 0.049
  CI (99.9%): [3.210, 4.989] (assumes normal distribution)


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
Iteration   1: 3.229 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.230 ms/op
                 createUser·p0.999:  11.632 ms/op
                 createUser·p0.9999: 18.451 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   2: 3.185 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.459 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  12.209 ms/op
                 createUser·p0.9999: 14.825 ms/op
                 createUser·p1.00:   15.483 ms/op

Iteration   3: 3.212 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  15.322 ms/op
                 createUser·p0.9999: 18.712 ms/op
                 createUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298977
  mean =      3.209 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10551 
    [ 2.500,  5.000) = 285672 
    [ 5.000,  7.500) = 1938 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =     12.175 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     19.911 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.075 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  12.604 ms/op
                 existUser·p0.9999: 22.858 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  7.709 ms/op
                 existUser·p0.9999: 15.278 ms/op
                 existUser·p1.00:   15.581 ms/op

Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  10.037 ms/op
                 existUser·p0.9999: 20.597 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313294
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20066 
    [ 2.500,  5.000) = 291285 
    [ 5.000,  7.500) = 1406 
    [ 7.500, 10.000) = 293 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     23.158 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 4.501 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.008 ms/op
Iteration   1: 3.211 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  10.322 ms/op
                 getUser·p0.9999: 16.499 ms/op
                 getUser·p1.00:   16.597 ms/op

Iteration   2: 3.215 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.131 ms/op
                 getUser·p0.9999: 19.892 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   3: 3.161 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.513 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  6.899 ms/op
                 getUser·p0.9999: 19.559 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300264
  mean =      3.196 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9348 
    [ 2.500,  5.000) = 288806 
    [ 5.000,  7.500) = 1524 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      9.183 ms/op
     p(99.9900) =     18.840 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 5.274 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.010 ms/op
Iteration   1: 4.033 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.200 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 3.890 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.046 ms/op
                 listUser·p0.9999: 20.432 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   3: 3.998 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  16.532 ms/op
                 listUser·p0.9999: 23.560 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241645
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2845 
    [ 2.500,  5.000) = 222608 
    [ 5.000,  7.500) = 14840 
    [ 7.500, 10.000) = 729 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     15.259 ms/op
     p(99.9900) =     20.311 ms/op
     p(99.9990) =     23.801 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.887 ± 3.169  ops/ms
ClientGrpc.existUser                       thrpt       3  10.432 ± 2.203  ops/ms
ClientGrpc.getUser                         thrpt       3  10.074 ± 1.069  ops/ms
ClientGrpc.listUser                        thrpt       3   8.090 ± 3.165  ops/ms
ClientGrpc.createUser                       avgt       3   3.229 ± 0.451   ms/op
ClientGrpc.existUser                        avgt       3   3.065 ± 0.462   ms/op
ClientGrpc.getUser                          avgt       3   3.186 ± 1.148   ms/op
ClientGrpc.listUser                         avgt       3   4.099 ± 0.889   ms/op
ClientGrpc.createUser                     sample  298977   3.209 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.459           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.154           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.039           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.175           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.859           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.231           ms/op
ClientGrpc.existUser                      sample  313294   3.065 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.762           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.612           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.978           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.480           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.200           ms/op
ClientGrpc.getUser                        sample  300264   3.196 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.513           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.183           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.840           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.775           ms/op
ClientGrpc.listUser                       sample  241645   3.972 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.869           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.259           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.311           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.855           ms/op
