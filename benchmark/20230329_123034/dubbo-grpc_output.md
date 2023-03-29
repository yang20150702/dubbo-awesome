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
# Warmup Iteration   1: 3.824 ops/ms
# Warmup Iteration   2: 8.093 ops/ms
# Warmup Iteration   3: 8.769 ops/ms
Iteration   1: 9.794 ops/ms
Iteration   2: 9.781 ops/ms
Iteration   3: 10.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.967 ±(99.9%) 5.679 ops/ms [Average]
  (min, avg, max) = (9.781, 9.967, 10.326), stdev = 0.311
  CI (99.9%): [4.288, 15.645] (assumes normal distribution)


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
# Warmup Iteration   1: 7.109 ops/ms
# Warmup Iteration   2: 10.304 ops/ms
# Warmup Iteration   3: 11.017 ops/ms
Iteration   1: 10.601 ops/ms
Iteration   2: 10.965 ops/ms
Iteration   3: 10.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.644 ±(99.9%) 5.514 ops/ms [Average]
  (min, avg, max) = (10.365, 10.644, 10.965), stdev = 0.302
  CI (99.9%): [5.130, 16.158] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.560 ops/ms
# Warmup Iteration   2: 9.585 ops/ms
# Warmup Iteration   3: 10.177 ops/ms
Iteration   1: 10.098 ops/ms
Iteration   2: 10.365 ops/ms
Iteration   3: 10.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.196 ±(99.9%) 2.676 ops/ms [Average]
  (min, avg, max) = (10.098, 10.196, 10.365), stdev = 0.147
  CI (99.9%): [7.519, 12.872] (assumes normal distribution)


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
# Warmup Iteration   1: 5.205 ops/ms
# Warmup Iteration   2: 7.187 ops/ms
# Warmup Iteration   3: 7.385 ops/ms
Iteration   1: 7.217 ops/ms
Iteration   2: 7.751 ops/ms
Iteration   3: 7.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.523 ±(99.9%) 5.020 ops/ms [Average]
  (min, avg, max) = (7.217, 7.523, 7.751), stdev = 0.275
  CI (99.9%): [2.503, 12.544] (assumes normal distribution)


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
# Warmup Iteration   1: 4.450 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.005 ms/op
Iteration   1: 3.189 ±(99.9%) 0.002 ms/op
Iteration   2: 3.128 ±(99.9%) 0.003 ms/op
Iteration   3: 3.168 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.161 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (3.128, 3.161, 3.189), stdev = 0.031
  CI (99.9%): [2.593, 3.730] (assumes normal distribution)


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.002 ms/op
Iteration   2: 3.082 ±(99.9%) 0.001 ms/op
Iteration   3: 3.165 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.107 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (3.076, 3.107, 3.165), stdev = 0.050
  CI (99.9%): [2.198, 4.016] (assumes normal distribution)


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
# Warmup Iteration   1: 4.715 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.002 ms/op
Iteration   1: 3.293 ±(99.9%) 0.003 ms/op
Iteration   2: 3.157 ±(99.9%) 0.002 ms/op
Iteration   3: 3.236 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.229 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (3.157, 3.229, 3.293), stdev = 0.069
  CI (99.9%): [1.977, 4.480] (assumes normal distribution)


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
# Warmup Iteration   1: 5.922 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.015 ms/op
Iteration   1: 4.135 ±(99.9%) 0.010 ms/op
Iteration   2: 4.146 ±(99.9%) 0.011 ms/op
Iteration   3: 4.184 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.155 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (4.135, 4.155, 4.184), stdev = 0.026
  CI (99.9%): [3.686, 4.623] (assumes normal distribution)


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
# Warmup Iteration   1: 4.586 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.008 ms/op
Iteration   1: 3.292 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  7.937 ms/op
                 createUser·p0.9999: 12.887 ms/op
                 createUser·p1.00:   13.844 ms/op

Iteration   2: 3.259 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  9.611 ms/op
                 createUser·p0.9999: 21.999 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   3: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.504 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.973 ms/op
                 createUser·p0.999:  9.603 ms/op
                 createUser·p0.9999: 19.562 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296276
  mean =      3.240 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21871 
    [ 2.500,  5.000) = 270822 
    [ 5.000,  7.500) = 3029 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =      8.777 ms/op
     p(99.9900) =     21.115 ms/op
     p(99.9990) =     22.351 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  7.589 ms/op
                 existUser·p0.9999: 19.944 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  6.965 ms/op
                 existUser·p0.9999: 22.381 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  7.327 ms/op
                 existUser·p0.9999: 22.035 ms/op
                 existUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314879
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38884 
    [ 2.500,  5.000) = 274168 
    [ 5.000,  7.500) = 1541 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.357 ms/op
     p(99.9900) =     21.873 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 4.669 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
Iteration   1: 3.194 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   5.058 ms/op
                 getUser·p0.999:  7.094 ms/op
                 getUser·p0.9999: 14.303 ms/op
                 getUser·p1.00:   15.794 ms/op

Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  7.964 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.586 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  6.914 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305447
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 984 
    [ 1.250,  2.500) = 28994 
    [ 2.500,  3.750) = 242502 
    [ 3.750,  5.000) = 30511 
    [ 5.000,  6.250) = 1782 
    [ 6.250,  7.500) = 418 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.825 ms/op
     p(99.9000) =      7.140 ms/op
     p(99.9900) =     16.669 ms/op
     p(99.9990) =     19.590 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 5.971 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.653 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.418 ±(99.9%) 0.013 ms/op
Iteration   1: 4.415 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   4.202 ms/op
                 listUser·p0.90:   5.693 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  14.444 ms/op
                 listUser·p0.9999: 20.464 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 4.355 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   4.219 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.491 ms/op
                 listUser·p0.999:  16.089 ms/op
                 listUser·p0.9999: 20.294 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 4.208 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  18.215 ms/op
                 listUser·p0.9999: 20.493 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 221995
  mean =      4.324 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1510 
    [ 2.500,  5.000) = 186216 
    [ 5.000,  7.500) = 31409 
    [ 7.500, 10.000) = 2170 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      4.157 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      6.193 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     21.570 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.967 ± 5.679  ops/ms
ClientGrpc.existUser                       thrpt       3  10.644 ± 5.514  ops/ms
ClientGrpc.getUser                         thrpt       3  10.196 ± 2.676  ops/ms
ClientGrpc.listUser                        thrpt       3   7.523 ± 5.020  ops/ms
ClientGrpc.createUser                       avgt       3   3.161 ± 0.569   ms/op
ClientGrpc.existUser                        avgt       3   3.107 ± 0.909   ms/op
ClientGrpc.getUser                          avgt       3   3.229 ± 1.251   ms/op
ClientGrpc.listUser                         avgt       3   4.155 ± 0.469   ms/op
ClientGrpc.createUser                     sample  296276   3.240 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.504           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.211           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.157           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.169           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.777           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.115           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.512           ms/op
ClientGrpc.existUser                      sample  314879   3.047 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.638           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.011           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.604           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.357           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.873           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.200           ms/op
ClientGrpc.getUser                        sample  305447   3.143 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.585           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.039           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.825           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.140           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.669           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.825           ms/op
ClientGrpc.listUser                       sample  221995   4.324 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.825           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.157           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.193           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.774           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.056           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.414           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.020           ms/op
