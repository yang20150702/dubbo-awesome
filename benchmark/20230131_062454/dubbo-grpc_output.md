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
# Warmup Iteration   1: 4.144 ops/ms
# Warmup Iteration   2: 8.875 ops/ms
# Warmup Iteration   3: 10.113 ops/ms
Iteration   1: 10.328 ops/ms
Iteration   2: 10.448 ops/ms
Iteration   3: 9.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.226 ±(99.9%) 5.228 ops/ms [Average]
  (min, avg, max) = (9.903, 10.226, 10.448), stdev = 0.287
  CI (99.9%): [4.998, 15.454] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.430 ops/ms
# Warmup Iteration   2: 10.070 ops/ms
# Warmup Iteration   3: 10.514 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.698 ops/ms
Iteration   3: 10.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.553 ±(99.9%) 3.186 ops/ms [Average]
  (min, avg, max) = (10.359, 10.553, 10.698), stdev = 0.175
  CI (99.9%): [7.367, 13.739] (assumes normal distribution)


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
# Warmup Iteration   1: 6.846 ops/ms
# Warmup Iteration   2: 9.485 ops/ms
# Warmup Iteration   3: 9.781 ops/ms
Iteration   1: 9.839 ops/ms
Iteration   2: 10.005 ops/ms
Iteration   3: 9.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.906 ±(99.9%) 1.600 ops/ms [Average]
  (min, avg, max) = (9.839, 9.906, 10.005), stdev = 0.088
  CI (99.9%): [8.306, 11.505] (assumes normal distribution)


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
# Warmup Iteration   1: 5.994 ops/ms
# Warmup Iteration   2: 7.323 ops/ms
# Warmup Iteration   3: 7.519 ops/ms
Iteration   1: 7.557 ops/ms
Iteration   2: 8.038 ops/ms
Iteration   3: 7.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.712 ±(99.9%) 5.156 ops/ms [Average]
  (min, avg, max) = (7.541, 7.712, 8.038), stdev = 0.283
  CI (99.9%): [2.556, 12.868] (assumes normal distribution)


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
# Warmup Iteration   1: 4.432 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.003 ms/op
Iteration   1: 3.246 ±(99.9%) 0.002 ms/op
Iteration   2: 3.245 ±(99.9%) 0.003 ms/op
Iteration   3: 3.269 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.254 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (3.245, 3.254, 3.269), stdev = 0.014
  CI (99.9%): [3.006, 3.501] (assumes normal distribution)


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
# Warmup Iteration   1: 4.287 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.002 ms/op
Iteration   1: 3.143 ±(99.9%) 0.002 ms/op
Iteration   2: 3.108 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.097 ±(99.9%) 0.952 ms/op [Average]
  (min, avg, max) = (3.041, 3.097, 3.143), stdev = 0.052
  CI (99.9%): [2.145, 4.050] (assumes normal distribution)


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.002 ms/op
Iteration   1: 3.293 ±(99.9%) 0.002 ms/op
Iteration   2: 3.317 ±(99.9%) 0.002 ms/op
Iteration   3: 3.237 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.282 ±(99.9%) 0.748 ms/op [Average]
  (min, avg, max) = (3.237, 3.282, 3.317), stdev = 0.041
  CI (99.9%): [2.534, 4.030] (assumes normal distribution)


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
# Warmup Iteration   1: 6.189 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.021 ms/op
Iteration   1: 4.193 ±(99.9%) 0.016 ms/op
Iteration   2: 4.217 ±(99.9%) 0.015 ms/op
Iteration   3: 4.128 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.179 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (4.128, 4.179, 4.217), stdev = 0.046
  CI (99.9%): [3.343, 5.015] (assumes normal distribution)


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
# Warmup Iteration   1: 4.537 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.007 ms/op
Iteration   1: 3.248 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.706 ms/op
                 createUser·p0.9999: 19.366 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   2: 3.248 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  12.804 ms/op
                 createUser·p0.9999: 20.747 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   3: 3.268 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  7.911 ms/op
                 createUser·p0.9999: 15.834 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294993
  mean =      3.254 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19191 
    [ 2.500,  5.000) = 274072 
    [ 5.000,  7.500) = 1289 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     20.431 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 4.276 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
Iteration   1: 3.077 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.873 ms/op
                 existUser·p0.9999: 13.625 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.045 ms/op
                 existUser·p0.9999: 26.837 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  10.648 ms/op
                 existUser·p0.9999: 16.392 ms/op
                 existUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313051
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37069 
    [ 2.500,  5.000) = 274394 
    [ 5.000,  7.500) = 1155 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     26.291 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 4.372 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.007 ms/op
Iteration   1: 3.197 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.700 ms/op
                 getUser·p0.9999: 13.663 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  8.142 ms/op
                 getUser·p0.9999: 22.020 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.117 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.893 ms/op
                 getUser·p0.9999: 18.514 ms/op
                 getUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303561
  mean =      3.162 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17801 
    [ 2.500,  5.000) = 283676 
    [ 5.000,  7.500) = 1659 
    [ 7.500, 10.000) = 225 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      8.231 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     22.149 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 4.763 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.013 ms/op
Iteration   1: 4.063 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.158 ms/op
                 listUser·p0.9999: 17.470 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   2: 4.106 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.123 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 4.108 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  16.338 ms/op
                 listUser·p0.9999: 22.086 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234393
  mean =      4.092 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2587 
    [ 2.500,  5.000) = 202897 
    [ 5.000,  7.500) = 27613 
    [ 7.500, 10.000) = 915 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     16.132 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     23.188 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.226 ± 5.228  ops/ms
ClientGrpc.existUser                       thrpt       3  10.553 ± 3.186  ops/ms
ClientGrpc.getUser                         thrpt       3   9.906 ± 1.600  ops/ms
ClientGrpc.listUser                        thrpt       3   7.712 ± 5.156  ops/ms
ClientGrpc.createUser                       avgt       3   3.254 ± 0.247   ms/op
ClientGrpc.existUser                        avgt       3   3.097 ± 0.952   ms/op
ClientGrpc.getUser                          avgt       3   3.282 ± 0.748   ms/op
ClientGrpc.listUser                         avgt       3   4.179 ± 0.836   ms/op
ClientGrpc.createUser                     sample  294993   3.254 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.782           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.215           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.162           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.782           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.431           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.004           ms/op
ClientGrpc.existUser                      sample  313051   3.067 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.650           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.039           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.936           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.765           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.291           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.066           ms/op
ClientGrpc.getUser                        sample  303561   3.162 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.665           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.231           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.611           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.462           ms/op
ClientGrpc.listUser                       sample  234393   4.092 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.087           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.928           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.132           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.791           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.200           ms/op
