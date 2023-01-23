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
# Warmup Iteration   1: 2.355 ops/ms
# Warmup Iteration   2: 6.175 ops/ms
# Warmup Iteration   3: 7.302 ops/ms
Iteration   1: 7.127 ops/ms
Iteration   2: 7.353 ops/ms
Iteration   3: 7.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.224 ±(99.9%) 2.131 ops/ms [Average]
  (min, avg, max) = (7.127, 7.224, 7.353), stdev = 0.117
  CI (99.9%): [5.093, 9.354] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.211 ops/ms
# Warmup Iteration   2: 7.618 ops/ms
# Warmup Iteration   3: 7.995 ops/ms
Iteration   1: 8.050 ops/ms
Iteration   2: 8.001 ops/ms
Iteration   3: 7.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.962 ±(99.9%) 2.062 ops/ms [Average]
  (min, avg, max) = (7.834, 7.962, 8.050), stdev = 0.113
  CI (99.9%): [5.899, 10.024] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.372 ops/ms
# Warmup Iteration   2: 6.976 ops/ms
# Warmup Iteration   3: 7.331 ops/ms
Iteration   1: 7.357 ops/ms
Iteration   2: 7.388 ops/ms
Iteration   3: 7.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.412 ±(99.9%) 1.276 ops/ms [Average]
  (min, avg, max) = (7.357, 7.412, 7.491), stdev = 0.070
  CI (99.9%): [6.136, 8.688] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.680 ops/ms
# Warmup Iteration   2: 5.456 ops/ms
# Warmup Iteration   3: 5.989 ops/ms
Iteration   1: 5.921 ops/ms
Iteration   2: 6.219 ops/ms
Iteration   3: 5.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.033 ±(99.9%) 2.967 ops/ms [Average]
  (min, avg, max) = (5.921, 6.033, 6.219), stdev = 0.163
  CI (99.9%): [3.066, 9.000] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.396 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.004 ms/op
Iteration   1: 4.329 ±(99.9%) 0.004 ms/op
Iteration   2: 4.395 ±(99.9%) 0.003 ms/op
Iteration   3: 4.311 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.345 ±(99.9%) 0.806 ms/op [Average]
  (min, avg, max) = (4.311, 4.345, 4.395), stdev = 0.044
  CI (99.9%): [3.539, 5.151] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.605 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.003 ms/op
Iteration   1: 4.016 ±(99.9%) 0.004 ms/op
Iteration   2: 4.174 ±(99.9%) 0.003 ms/op
Iteration   3: 4.188 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.126 ±(99.9%) 1.744 ms/op [Average]
  (min, avg, max) = (4.016, 4.126, 4.188), stdev = 0.096
  CI (99.9%): [2.381, 5.870] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.310 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.677 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.373 ±(99.9%) 0.003 ms/op
Iteration   1: 4.244 ±(99.9%) 0.005 ms/op
Iteration   2: 4.307 ±(99.9%) 0.004 ms/op
Iteration   3: 4.259 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.270 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (4.244, 4.270, 4.307), stdev = 0.033
  CI (99.9%): [3.677, 4.863] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.578 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.731 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.405 ±(99.9%) 0.017 ms/op
Iteration   1: 5.472 ±(99.9%) 0.011 ms/op
Iteration   2: 5.436 ±(99.9%) 0.012 ms/op
Iteration   3: 5.396 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.435 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (5.396, 5.435, 5.472), stdev = 0.038
  CI (99.9%): [4.741, 6.129] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.491 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.556 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.269 ±(99.9%) 0.012 ms/op
Iteration   1: 4.221 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   4.084 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   7.278 ms/op
                 createUser·p0.999:  13.418 ms/op
                 createUser·p0.9999: 18.485 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   2: 4.309 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.751 ms/op
                 createUser·p0.99:   7.264 ms/op
                 createUser·p0.999:  12.135 ms/op
                 createUser·p0.9999: 21.832 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   3: 4.302 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.425 ms/op
                 createUser·p0.50:   4.190 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.775 ms/op
                 createUser·p0.99:   6.758 ms/op
                 createUser·p0.999:  21.889 ms/op
                 createUser·p0.9999: 28.574 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224484
  mean =      4.277 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3196 
    [ 2.500,  5.000) = 181458 
    [ 5.000,  7.500) = 38084 
    [ 7.500, 10.000) = 1233 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      4.153 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     27.918 ms/op
     p(99.9990) =     28.944 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.495 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.012 ms/op
Iteration   1: 4.002 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   5.071 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   6.984 ms/op
                 existUser·p0.999:  12.859 ms/op
                 existUser·p0.9999: 16.253 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   2: 4.096 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   4.022 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  11.615 ms/op
                 existUser·p0.9999: 16.431 ms/op
                 existUser·p1.00:   18.776 ms/op

Iteration   3: 4.170 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   4.116 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.530 ms/op
                 existUser·p0.99:   6.545 ms/op
                 existUser·p0.999:  9.392 ms/op
                 existUser·p0.9999: 19.245 ms/op
                 existUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 234895
  mean =      4.088 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 7365 
    [ 2.500,  3.750) = 79866 
    [ 3.750,  5.000) = 115595 
    [ 5.000,  6.250) = 28544 
    [ 6.250,  7.500) = 2101 
    [ 7.500,  8.750) = 668 
    [ 8.750, 10.000) = 330 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     11.321 ms/op
     p(99.9900) =     18.646 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.111 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.659 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.430 ±(99.9%) 0.013 ms/op
Iteration   1: 4.417 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.669 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   7.232 ms/op
                 getUser·p0.999:  13.887 ms/op
                 getUser·p0.9999: 16.331 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   2: 4.265 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   4.190 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  14.287 ms/op
                 getUser·p0.9999: 19.038 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   3: 4.401 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  11.026 ms/op
                 getUser·p0.9999: 19.512 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 220149
  mean =      4.360 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4532 
    [ 2.500,  5.000) = 166650 
    [ 5.000,  7.500) = 47382 
    [ 7.500, 10.000) = 1109 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     20.028 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 7.934 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.909 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.373 ±(99.9%) 0.019 ms/op
Iteration   1: 5.127 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  18.306 ms/op
                 listUser·p0.9999: 22.005 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 5.306 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   5.071 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  17.390 ms/op
                 listUser·p0.9999: 19.855 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 5.212 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.636 ms/op
                 listUser·p0.50:   4.997 ms/op
                 listUser·p0.90:   6.799 ms/op
                 listUser·p0.95:   7.550 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  18.657 ms/op
                 listUser·p0.9999: 21.033 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 183958
  mean =      5.214 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 284 
    [ 2.500,  5.000) = 93043 
    [ 5.000,  7.500) = 79997 
    [ 7.500, 10.000) = 9102 
    [10.000, 12.500) = 1056 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =      9.748 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     22.434 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.224 ± 2.131  ops/ms
ClientGrpc.existUser                       thrpt       3   7.962 ± 2.062  ops/ms
ClientGrpc.getUser                         thrpt       3   7.412 ± 1.276  ops/ms
ClientGrpc.listUser                        thrpt       3   6.033 ± 2.967  ops/ms
ClientGrpc.createUser                       avgt       3   4.345 ± 0.806   ms/op
ClientGrpc.existUser                        avgt       3   4.126 ± 1.744   ms/op
ClientGrpc.getUser                          avgt       3   4.270 ± 0.593   ms/op
ClientGrpc.listUser                         avgt       3   5.435 ± 0.694   ms/op
ClientGrpc.createUser                     sample  224484   4.277 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.425           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.153           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.374           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.751           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.094           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.550           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.918           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.426           ms/op
ClientGrpc.existUser                      sample  234895   4.088 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.163           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.014           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.169           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.497           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.717           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.321           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.646           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.497           ms/op
ClientGrpc.getUser                        sample  220149   4.360 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.133           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.505           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.849           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.045           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.222           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.071           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  183958   5.214 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.618           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.660           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.748           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.957           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.398           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.544           ms/op
