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
# Warmup Iteration   1: 3.552 ops/ms
# Warmup Iteration   2: 7.251 ops/ms
# Warmup Iteration   3: 8.405 ops/ms
Iteration   1: 8.896 ops/ms
Iteration   2: 9.235 ops/ms
Iteration   3: 9.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.165 ±(99.9%) 4.405 ops/ms [Average]
  (min, avg, max) = (8.896, 9.165, 9.364), stdev = 0.241
  CI (99.9%): [4.761, 13.570] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.418 ops/ms
# Warmup Iteration   2: 8.960 ops/ms
# Warmup Iteration   3: 9.597 ops/ms
Iteration   1: 9.438 ops/ms
Iteration   2: 9.647 ops/ms
Iteration   3: 9.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.526 ±(99.9%) 1.984 ops/ms [Average]
  (min, avg, max) = (9.438, 9.526, 9.647), stdev = 0.109
  CI (99.9%): [7.542, 11.510] (assumes normal distribution)


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
# Warmup Iteration   1: 5.902 ops/ms
# Warmup Iteration   2: 9.258 ops/ms
# Warmup Iteration   3: 9.415 ops/ms
Iteration   1: 9.810 ops/ms
Iteration   2: 9.305 ops/ms
Iteration   3: 9.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.515 ±(99.9%) 4.790 ops/ms [Average]
  (min, avg, max) = (9.305, 9.515, 9.810), stdev = 0.263
  CI (99.9%): [4.725, 14.306] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.690 ops/ms
# Warmup Iteration   2: 7.033 ops/ms
# Warmup Iteration   3: 7.408 ops/ms
Iteration   1: 7.364 ops/ms
Iteration   2: 7.403 ops/ms
Iteration   3: 7.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.385 ±(99.9%) 0.359 ops/ms [Average]
  (min, avg, max) = (7.364, 7.385, 7.403), stdev = 0.020
  CI (99.9%): [7.025, 7.744] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.122 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.003 ms/op
Iteration   1: 3.303 ±(99.9%) 0.010 ms/op
Iteration   2: 3.534 ±(99.9%) 0.002 ms/op
Iteration   3: 3.502 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.446 ±(99.9%) 2.281 ms/op [Average]
  (min, avg, max) = (3.303, 3.446, 3.534), stdev = 0.125
  CI (99.9%): [1.165, 5.727] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.004 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.003 ms/op
Iteration   1: 3.191 ±(99.9%) 0.003 ms/op
Iteration   2: 3.243 ±(99.9%) 0.003 ms/op
Iteration   3: 3.047 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.160 ±(99.9%) 1.847 ms/op [Average]
  (min, avg, max) = (3.047, 3.160, 3.243), stdev = 0.101
  CI (99.9%): [1.313, 5.008] (assumes normal distribution)


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
# Warmup Iteration   1: 4.905 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.523 ±(99.9%) 0.006 ms/op
Iteration   1: 3.493 ±(99.9%) 0.002 ms/op
Iteration   2: 3.503 ±(99.9%) 0.004 ms/op
Iteration   3: 3.439 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.479 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (3.439, 3.479, 3.503), stdev = 0.034
  CI (99.9%): [2.853, 4.104] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.024 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.728 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.476 ±(99.9%) 0.012 ms/op
Iteration   1: 4.536 ±(99.9%) 0.014 ms/op
Iteration   2: 4.470 ±(99.9%) 0.020 ms/op
Iteration   3: 4.325 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.443 ±(99.9%) 1.967 ms/op [Average]
  (min, avg, max) = (4.325, 4.443, 4.536), stdev = 0.108
  CI (99.9%): [2.477, 6.410] (assumes normal distribution)


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
# Warmup Iteration   1: 4.642 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.008 ms/op
Iteration   1: 3.390 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  8.348 ms/op
                 createUser·p0.9999: 20.531 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   2: 3.505 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  8.512 ms/op
                 createUser·p0.9999: 21.520 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   3: 3.483 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  11.535 ms/op
                 createUser·p0.9999: 23.226 ms/op
                 createUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 277719
  mean =      3.458 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9658 
    [ 2.500,  5.000) = 263794 
    [ 5.000,  7.500) = 3697 
    [ 7.500, 10.000) = 327 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     22.912 ms/op
     p(99.9990) =     23.411 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 4.791 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.007 ms/op
Iteration   1: 3.227 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.347 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   4.981 ms/op
                 existUser·p0.999:  9.567 ms/op
                 existUser·p0.9999: 14.388 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   2: 3.233 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  6.750 ms/op
                 existUser·p0.9999: 29.858 ms/op
                 existUser·p1.00:   30.310 ms/op

Iteration   3: 3.373 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  11.094 ms/op
                 existUser·p0.9999: 18.809 ms/op
                 existUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 292927
  mean =      3.276 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16150 
    [ 2.500,  5.000) = 274001 
    [ 5.000,  7.500) = 2281 
    [ 7.500, 10.000) = 246 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.347 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =      8.963 ms/op
     p(99.9900) =     29.285 ms/op
     p(99.9990) =     30.214 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.387 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.008 ms/op
Iteration   1: 3.484 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  11.727 ms/op
                 getUser·p0.9999: 15.679 ms/op
                 getUser·p1.00:   15.843 ms/op

Iteration   2: 3.314 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  10.038 ms/op
                 getUser·p0.9999: 23.615 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   3: 3.365 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.054 ms/op
                 getUser·p0.999:  7.550 ms/op
                 getUser·p0.9999: 18.809 ms/op
                 getUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 283589
  mean =      3.386 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13045 
    [ 2.500,  5.000) = 265534 
    [ 5.000,  7.500) = 4356 
    [ 7.500, 10.000) = 385 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     21.308 ms/op
     p(99.9990) =     23.997 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 5.812 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.789 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.554 ±(99.9%) 0.015 ms/op
Iteration   1: 4.431 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   4.252 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  17.357 ms/op
                 listUser·p0.9999: 22.366 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   2: 4.282 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   4.121 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  17.988 ms/op
                 listUser·p0.9999: 24.135 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   3: 4.383 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   4.227 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  21.529 ms/op
                 listUser·p0.9999: 29.026 ms/op
                 listUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 219816
  mean =      4.365 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 959 
    [ 2.500,  5.000) = 188865 
    [ 5.000,  7.500) = 27214 
    [ 7.500, 10.000) = 2258 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      6.201 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     18.782 ms/op
     p(99.9900) =     27.428 ms/op
     p(99.9990) =     29.865 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.165 ± 4.405  ops/ms
ClientGrpc.existUser                       thrpt       3   9.526 ± 1.984  ops/ms
ClientGrpc.getUser                         thrpt       3   9.515 ± 4.790  ops/ms
ClientGrpc.listUser                        thrpt       3   7.385 ± 0.359  ops/ms
ClientGrpc.createUser                       avgt       3   3.446 ± 2.281   ms/op
ClientGrpc.existUser                        avgt       3   3.160 ± 1.847   ms/op
ClientGrpc.getUser                          avgt       3   3.479 ± 0.625   ms/op
ClientGrpc.listUser                         avgt       3   4.443 ± 1.967   ms/op
ClientGrpc.createUser                     sample  277719   3.458 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.692           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.416           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.341           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.815           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.912           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.527           ms/op
ClientGrpc.existUser                      sample  292927   3.276 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.347           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.260           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.964           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.963           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.285           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.310           ms/op
ClientGrpc.getUser                        sample  283589   3.386 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.733           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.338           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.022           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.554           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.568           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.308           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.117           ms/op
ClientGrpc.listUser                       sample  219816   4.365 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.149           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.202           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.201           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.725           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.782           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.428           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.983           ms/op
