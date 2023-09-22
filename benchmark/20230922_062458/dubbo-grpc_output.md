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
# Warmup Iteration   1: 4.344 ops/ms
# Warmup Iteration   2: 8.924 ops/ms
# Warmup Iteration   3: 9.868 ops/ms
Iteration   1: 10.271 ops/ms
Iteration   2: 10.292 ops/ms
Iteration   3: 10.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.225 ±(99.9%) 1.780 ops/ms [Average]
  (min, avg, max) = (10.113, 10.225, 10.292), stdev = 0.098
  CI (99.9%): [8.445, 12.005] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.434 ops/ms
# Warmup Iteration   2: 10.312 ops/ms
# Warmup Iteration   3: 10.552 ops/ms
Iteration   1: 10.561 ops/ms
Iteration   2: 10.668 ops/ms
Iteration   3: 11.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.755 ±(99.9%) 4.540 ops/ms [Average]
  (min, avg, max) = (10.561, 10.755, 11.036), stdev = 0.249
  CI (99.9%): [6.215, 15.295] (assumes normal distribution)


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
# Warmup Iteration   1: 6.603 ops/ms
# Warmup Iteration   2: 9.857 ops/ms
# Warmup Iteration   3: 10.215 ops/ms
Iteration   1: 10.179 ops/ms
Iteration   2: 10.073 ops/ms
Iteration   3: 10.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.152 ±(99.9%) 1.271 ops/ms [Average]
  (min, avg, max) = (10.073, 10.152, 10.204), stdev = 0.070
  CI (99.9%): [8.881, 11.423] (assumes normal distribution)


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
# Warmup Iteration   1: 4.949 ops/ms
# Warmup Iteration   2: 7.785 ops/ms
# Warmup Iteration   3: 8.048 ops/ms
Iteration   1: 7.818 ops/ms
Iteration   2: 7.523 ops/ms
Iteration   3: 7.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.684 ±(99.9%) 2.724 ops/ms [Average]
  (min, avg, max) = (7.523, 7.684, 7.818), stdev = 0.149
  CI (99.9%): [4.960, 10.408] (assumes normal distribution)


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
# Warmup Iteration   1: 4.322 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.002 ms/op
Iteration   1: 3.250 ±(99.9%) 0.002 ms/op
Iteration   2: 4.002 ±(99.9%) 0.003 ms/op
Iteration   3: 4.118 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.790 ±(99.9%) 8.596 ms/op [Average]
  (min, avg, max) = (3.250, 3.790, 4.118), stdev = 0.471
  CI (99.9%): [≈ 0, 12.386] (assumes normal distribution)


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
# Warmup Iteration   1: 5.554 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.002 ms/op
Iteration   1: 3.650 ±(99.9%) 0.003 ms/op
Iteration   2: 3.430 ±(99.9%) 0.004 ms/op
Iteration   3: 3.853 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.644 ±(99.9%) 3.862 ms/op [Average]
  (min, avg, max) = (3.430, 3.644, 3.853), stdev = 0.212
  CI (99.9%): [≈ 0, 7.506] (assumes normal distribution)


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
# Warmup Iteration   1: 5.234 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.005 ms/op
Iteration   1: 3.745 ±(99.9%) 0.003 ms/op
Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
Iteration   3: 3.313 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.609 ±(99.9%) 4.677 ms/op [Average]
  (min, avg, max) = (3.313, 3.609, 3.768), stdev = 0.256
  CI (99.9%): [≈ 0, 8.286] (assumes normal distribution)


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
# Warmup Iteration   1: 4.933 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.437 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.006 ms/op
Iteration   1: 4.103 ±(99.9%) 0.029 ms/op
Iteration   2: 4.496 ±(99.9%) 0.015 ms/op
Iteration   3: 4.601 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.400 ±(99.9%) 4.789 ms/op [Average]
  (min, avg, max) = (4.103, 4.400, 4.601), stdev = 0.262
  CI (99.9%): [≈ 0, 9.189] (assumes normal distribution)


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
# Warmup Iteration   1: 4.886 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.011 ms/op
Iteration   1: 3.409 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  11.841 ms/op
                 createUser·p0.9999: 19.865 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   2: 3.303 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  13.369 ms/op
                 createUser·p0.9999: 18.485 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 3.245 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.148 ms/op
                 createUser·p0.999:  11.846 ms/op
                 createUser·p0.9999: 18.949 ms/op
                 createUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 289232
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16803 
    [ 2.500,  5.000) = 265605 
    [ 5.000,  7.500) = 5096 
    [ 7.500, 10.000) = 1145 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     12.481 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     20.123 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 4.701 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
Iteration   1: 3.173 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  9.766 ms/op
                 existUser·p0.9999: 13.663 ms/op
                 existUser·p1.00:   15.974 ms/op

Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  10.521 ms/op
                 existUser·p0.9999: 15.827 ms/op
                 existUser·p1.00:   16.056 ms/op

Iteration   3: 3.156 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.428 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   6.550 ms/op
                 existUser·p0.999:  11.588 ms/op
                 existUser·p0.9999: 18.706 ms/op
                 existUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 301260
  mean =      3.187 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1197 
    [ 1.250,  2.500) = 17299 
    [ 2.500,  3.750) = 249929 
    [ 3.750,  5.000) = 26402 
    [ 5.000,  6.250) = 3546 
    [ 6.250,  7.500) = 1370 
    [ 7.500,  8.750) = 836 
    [ 8.750, 10.000) = 292 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     10.514 ms/op
     p(99.9900) =     17.854 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.008 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.749 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  8.318 ms/op
                 getUser·p0.9999: 13.091 ms/op
                 getUser·p1.00:   13.353 ms/op

Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  9.832 ms/op
                 getUser·p0.9999: 16.247 ms/op
                 getUser·p1.00:   16.564 ms/op

Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.997 ms/op
                 getUser·p0.999:  7.864 ms/op
                 getUser·p0.9999: 17.013 ms/op
                 getUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308735
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1074 
    [ 1.250,  2.500) = 14356 
    [ 2.500,  3.750) = 271227 
    [ 3.750,  5.000) = 19342 
    [ 5.000,  6.250) = 1541 
    [ 6.250,  7.500) = 622 
    [ 7.500,  8.750) = 236 
    [ 8.750, 10.000) = 141 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.891 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     16.454 ms/op
     p(99.9990) =     17.877 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 5.760 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.012 ms/op
Iteration   1: 4.039 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  13.988 ms/op
                 listUser·p0.9999: 23.305 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 4.019 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.506 ms/op
                 listUser·p0.9999: 17.860 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   3: 4.135 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.193 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 22.767 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236215
  mean =      4.064 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2945 
    [ 2.500,  5.000) = 209034 
    [ 5.000,  7.500) = 22261 
    [ 7.500, 10.000) = 1321 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     23.981 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.225 ± 1.780  ops/ms
ClientGrpc.existUser                       thrpt       3  10.755 ± 4.540  ops/ms
ClientGrpc.getUser                         thrpt       3  10.152 ± 1.271  ops/ms
ClientGrpc.listUser                        thrpt       3   7.684 ± 2.724  ops/ms
ClientGrpc.createUser                       avgt       3   3.790 ± 8.596   ms/op
ClientGrpc.existUser                        avgt       3   3.644 ± 3.862   ms/op
ClientGrpc.getUser                          avgt       3   3.609 ± 4.677   ms/op
ClientGrpc.listUser                         avgt       3   4.400 ± 4.789   ms/op
ClientGrpc.createUser                     sample  289232   3.318 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.695           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.240           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.035           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.357           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.481           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.973           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.218           ms/op
ClientGrpc.existUser                      sample  301260   3.187 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.428           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.117           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.152           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.514           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.854           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.956           ms/op
ClientGrpc.getUser                        sample  308735   3.110 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.749           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.891           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.897           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.454           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.055           ms/op
ClientGrpc.listUser                       sample  236215   4.064 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.188           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.972           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.446           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.117           ms/op
