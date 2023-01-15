# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.115 ops/ms
# Warmup Iteration   2: 9.255 ops/ms
# Warmup Iteration   3: 10.134 ops/ms
Iteration   1: 10.164 ops/ms
Iteration   2: 10.013 ops/ms
Iteration   3: 10.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.119 ±(99.9%) 1.675 ops/ms [Average]
  (min, avg, max) = (10.013, 10.119, 10.179), stdev = 0.092
  CI (99.9%): [8.444, 11.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.604 ops/ms
# Warmup Iteration   2: 10.245 ops/ms
# Warmup Iteration   3: 10.543 ops/ms
Iteration   1: 10.939 ops/ms
Iteration   2: 10.681 ops/ms
Iteration   3: 10.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.707 ±(99.9%) 4.010 ops/ms [Average]
  (min, avg, max) = (10.502, 10.707, 10.939), stdev = 0.220
  CI (99.9%): [6.697, 14.717] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.636 ops/ms
# Warmup Iteration   2: 10.071 ops/ms
# Warmup Iteration   3: 10.117 ops/ms
Iteration   1: 9.992 ops/ms
Iteration   2: 9.844 ops/ms
Iteration   3: 9.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.917 ±(99.9%) 1.346 ops/ms [Average]
  (min, avg, max) = (9.844, 9.917, 9.992), stdev = 0.074
  CI (99.9%): [8.571, 11.263] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.320 ops/ms
# Warmup Iteration   2: 7.464 ops/ms
# Warmup Iteration   3: 7.787 ops/ms
Iteration   1: 7.988 ops/ms
Iteration   2: 7.954 ops/ms
Iteration   3: 7.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.910 ±(99.9%) 1.960 ops/ms [Average]
  (min, avg, max) = (7.788, 7.910, 7.988), stdev = 0.107
  CI (99.9%): [5.950, 9.870] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.652 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.008 ms/op
Iteration   1: 3.109 ±(99.9%) 0.002 ms/op
Iteration   2: 3.121 ±(99.9%) 0.002 ms/op
Iteration   3: 3.202 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.144 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.109, 3.144, 3.202), stdev = 0.051
  CI (99.9%): [2.220, 4.069] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.998 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.001 ms/op
Iteration   1: 3.166 ±(99.9%) 0.002 ms/op
Iteration   2: 3.159 ±(99.9%) 0.001 ms/op
Iteration   3: 3.124 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.149 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (3.124, 3.149, 3.166), stdev = 0.022
  CI (99.9%): [2.743, 3.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.391 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.002 ms/op
Iteration   1: 3.192 ±(99.9%) 0.003 ms/op
Iteration   2: 3.195 ±(99.9%) 0.002 ms/op
Iteration   3: 3.177 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.188 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (3.177, 3.188, 3.195), stdev = 0.010
  CI (99.9%): [3.013, 3.363] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.236 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.033 ms/op
Iteration   1: 4.005 ±(99.9%) 0.025 ms/op
Iteration   2: 3.894 ±(99.9%) 0.024 ms/op
Iteration   3: 3.969 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.956 ±(99.9%) 1.037 ms/op [Average]
  (min, avg, max) = (3.894, 3.956, 4.005), stdev = 0.057
  CI (99.9%): [2.920, 4.993] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.281 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.233 ±(99.9%) 0.007 ms/op
Iteration   1: 3.104 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  6.390 ms/op
                 createUser·p0.9999: 19.847 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.393 ms/op
                 createUser·p0.999:  8.690 ms/op
                 createUser·p0.9999: 19.790 ms/op
                 createUser·p1.00:   20.087 ms/op

Iteration   3: 3.208 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  10.600 ms/op
                 createUser·p0.9999: 33.554 ms/op
                 createUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303437
  mean =      3.163 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26156 
    [ 2.500,  5.000) = 275974 
    [ 5.000,  7.500) = 883 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     33.412 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.113 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  4.735 ms/op
                 existUser·p0.9999: 16.581 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  8.158 ms/op
                 existUser·p0.9999: 17.582 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.035 ms/op
                 existUser·p0.9999: 16.602 ms/op
                 existUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313473
  mean =      3.061 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1501 
    [ 1.250,  2.500) = 35774 
    [ 2.500,  3.750) = 242122 
    [ 3.750,  5.000) = 33269 
    [ 5.000,  6.250) = 339 
    [ 6.250,  7.500) = 233 
    [ 7.500,  8.750) = 87 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.045 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     17.887 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.313 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.007 ms/op
Iteration   1: 3.174 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.612 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  9.162 ms/op
                 getUser·p0.9999: 20.049 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.841 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.617 ms/op
                 getUser·p0.9999: 21.135 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   3: 3.216 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.364 ms/op
                 getUser·p0.9999: 22.547 ms/op
                 getUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301545
  mean =      3.183 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23041 
    [ 2.500,  5.000) = 277415 
    [ 5.000,  7.500) = 730 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.827 ms/op
     p(99.9900) =     21.687 ms/op
     p(99.9990) =     24.484 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.419 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.011 ms/op
Iteration   1: 4.119 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.639 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  12.409 ms/op
                 listUser·p0.9999: 16.437 ms/op
                 listUser·p1.00:   17.891 ms/op

Iteration   2: 4.013 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.144 ms/op
                 listUser·p0.999:  14.916 ms/op
                 listUser·p0.9999: 17.992 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   3: 4.033 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.868 ms/op
                 listUser·p0.999:  14.095 ms/op
                 listUser·p0.9999: 28.086 ms/op
                 listUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236776
  mean =      4.055 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3641 
    [ 2.500,  5.000) = 201823 
    [ 5.000,  7.500) = 29712 
    [ 7.500, 10.000) = 1177 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     14.036 ms/op
     p(99.9900) =     27.405 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.119 ± 1.675  ops/ms
ClientGrpc.existUser                       thrpt       3  10.707 ± 4.010  ops/ms
ClientGrpc.getUser                         thrpt       3   9.917 ± 1.346  ops/ms
ClientGrpc.listUser                        thrpt       3   7.910 ± 1.960  ops/ms
ClientGrpc.createUser                       avgt       3   3.144 ± 0.925   ms/op
ClientGrpc.existUser                        avgt       3   3.149 ± 0.407   ms/op
ClientGrpc.getUser                          avgt       3   3.188 ± 0.175   ms/op
ClientGrpc.listUser                         avgt       3   3.956 ± 1.037   ms/op
ClientGrpc.createUser                     sample  303437   3.163 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.551           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.077           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.412           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.979           ms/op
ClientGrpc.existUser                      sample  313473   3.061 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.641           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.039           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.944           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.045           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.039           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  301545   3.183 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.612           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.154           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.827           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.687           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.035           ms/op
ClientGrpc.listUser                       sample  236776   4.055 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.639           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.036           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.405           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.000           ms/op
