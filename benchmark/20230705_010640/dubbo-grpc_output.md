# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ops/ms
# Warmup Iteration   2: 8.348 ops/ms
# Warmup Iteration   3: 9.566 ops/ms
Iteration   1: 9.847 ops/ms
Iteration   2: 9.877 ops/ms
Iteration   3: 9.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.833 ±(99.9%) 0.961 ops/ms [Average]
  (min, avg, max) = (9.774, 9.833, 9.877), stdev = 0.053
  CI (99.9%): [8.871, 10.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.906 ops/ms
# Warmup Iteration   2: 10.013 ops/ms
# Warmup Iteration   3: 10.366 ops/ms
Iteration   1: 10.067 ops/ms
Iteration   2: 10.302 ops/ms
Iteration   3: 10.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.272 ±(99.9%) 3.493 ops/ms [Average]
  (min, avg, max) = (10.067, 10.272, 10.447), stdev = 0.191
  CI (99.9%): [6.779, 13.765] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.413 ops/ms
# Warmup Iteration   2: 9.323 ops/ms
# Warmup Iteration   3: 10.008 ops/ms
Iteration   1: 9.769 ops/ms
Iteration   2: 10.022 ops/ms
Iteration   3: 9.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.831 ±(99.9%) 3.068 ops/ms [Average]
  (min, avg, max) = (9.703, 9.831, 10.022), stdev = 0.168
  CI (99.9%): [6.763, 12.899] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.357 ops/ms
# Warmup Iteration   2: 6.904 ops/ms
# Warmup Iteration   3: 7.365 ops/ms
Iteration   1: 7.415 ops/ms
Iteration   2: 7.812 ops/ms
Iteration   3: 7.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.593 ±(99.9%) 3.680 ops/ms [Average]
  (min, avg, max) = (7.415, 7.593, 7.812), stdev = 0.202
  CI (99.9%): [3.913, 11.273] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.719 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.004 ms/op
Iteration   1: 3.291 ±(99.9%) 0.002 ms/op
Iteration   2: 3.138 ±(99.9%) 0.004 ms/op
Iteration   3: 3.313 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.247 ±(99.9%) 1.735 ms/op [Average]
  (min, avg, max) = (3.138, 3.247, 3.313), stdev = 0.095
  CI (99.9%): [1.513, 4.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.164 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.004 ms/op
Iteration   1: 3.262 ±(99.9%) 0.007 ms/op
Iteration   2: 3.130 ±(99.9%) 0.001 ms/op
Iteration   3: 3.135 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.176 ±(99.9%) 1.362 ms/op [Average]
  (min, avg, max) = (3.130, 3.176, 3.262), stdev = 0.075
  CI (99.9%): [1.814, 4.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.653 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.003 ms/op
Iteration   1: 3.329 ±(99.9%) 0.003 ms/op
Iteration   2: 3.345 ±(99.9%) 0.002 ms/op
Iteration   3: 3.328 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.334 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (3.328, 3.334, 3.345), stdev = 0.010
  CI (99.9%): [3.156, 3.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.821 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.012 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.422 ±(99.9%) 0.019 ms/op
Iteration   1: 4.345 ±(99.9%) 0.019 ms/op
Iteration   2: 4.362 ±(99.9%) 0.006 ms/op
Iteration   3: 4.253 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.320 ±(99.9%) 1.063 ms/op [Average]
  (min, avg, max) = (4.253, 4.320, 4.362), stdev = 0.058
  CI (99.9%): [3.257, 5.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.817 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.007 ms/op
Iteration   1: 3.433 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  8.040 ms/op
                 createUser·p0.9999: 19.694 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   2: 3.439 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.357 ms/op
                 createUser·p0.999:  9.732 ms/op
                 createUser·p0.9999: 25.507 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.553 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  10.712 ms/op
                 createUser·p0.9999: 20.120 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 276509
  mean =      3.474 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9022 
    [ 2.500,  5.000) = 262908 
    [ 5.000,  7.500) = 4075 
    [ 7.500, 10.000) = 297 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     24.446 ms/op
     p(99.9990) =     25.898 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.692 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.008 ms/op
Iteration   1: 3.254 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  7.368 ms/op
                 existUser·p0.9999: 14.421 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   2: 3.312 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  8.582 ms/op
                 existUser·p0.9999: 15.287 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   3: 3.300 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  10.238 ms/op
                 existUser·p0.9999: 31.425 ms/op
                 existUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 291896
  mean =      3.289 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10623 
    [ 2.500,  5.000) = 278239 
    [ 5.000,  7.500) = 2575 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.022 ms/op
     p(99.9000) =      8.898 ms/op
     p(99.9900) =     31.215 ms/op
     p(99.9990) =     31.602 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.810 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.008 ms/op
Iteration   1: 3.273 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  8.214 ms/op
                 getUser·p0.9999: 15.363 ms/op
                 getUser·p1.00:   15.729 ms/op

Iteration   2: 3.249 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  9.493 ms/op
                 getUser·p0.9999: 18.754 ms/op
                 getUser·p1.00:   19.235 ms/op

Iteration   3: 3.325 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  8.002 ms/op
                 getUser·p0.9999: 18.191 ms/op
                 getUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 292289
  mean =      3.282 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 220 
    [ 1.250,  2.500) = 14567 
    [ 2.500,  3.750) = 235322 
    [ 3.750,  5.000) = 39261 
    [ 5.000,  6.250) = 1964 
    [ 6.250,  7.500) = 494 
    [ 7.500,  8.750) = 223 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      4.997 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     18.138 ms/op
     p(99.9990) =     19.109 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.033 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.918 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.503 ±(99.9%) 0.013 ms/op
Iteration   1: 4.508 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  15.601 ms/op
                 listUser·p0.9999: 22.374 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   2: 4.342 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  15.668 ms/op
                 listUser·p0.9999: 19.625 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   3: 4.383 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   4.178 ms/op
                 listUser·p0.90:   5.702 ms/op
                 listUser·p0.95:   6.349 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  18.201 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 217686
  mean =      4.410 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1197 
    [ 2.500,  5.000) = 180045 
    [ 5.000,  7.500) = 32467 
    [ 7.500, 10.000) = 3441 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.472 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     23.051 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.833 ± 0.961  ops/ms
ClientGrpc.existUser                       thrpt       3  10.272 ± 3.493  ops/ms
ClientGrpc.getUser                         thrpt       3   9.831 ± 3.068  ops/ms
ClientGrpc.listUser                        thrpt       3   7.593 ± 3.680  ops/ms
ClientGrpc.createUser                       avgt       3   3.247 ± 1.735   ms/op
ClientGrpc.existUser                        avgt       3   3.176 ± 1.362   ms/op
ClientGrpc.getUser                          avgt       3   3.334 ± 0.178   ms/op
ClientGrpc.listUser                         avgt       3   4.320 ± 1.063   ms/op
ClientGrpc.createUser                     sample  276509   3.474 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.639           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.432           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.100           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.011           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.446           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.214           ms/op
ClientGrpc.existUser                      sample  291896   3.289 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.839           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.236           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.863           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.022           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.898           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.215           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.752           ms/op
ClientGrpc.getUser                        sample  292289   3.282 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.882           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.240           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.149           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.997           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.405           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.138           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.235           ms/op
ClientGrpc.listUser                       sample  217686   4.410 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.906           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.235           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.028           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.744           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.939           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.543           ms/op
