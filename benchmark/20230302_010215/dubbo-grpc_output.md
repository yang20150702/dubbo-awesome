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
# Warmup Iteration   1: 2.191 ops/ms
# Warmup Iteration   2: 5.425 ops/ms
# Warmup Iteration   3: 6.600 ops/ms
Iteration   1: 6.834 ops/ms
Iteration   2: 7.264 ops/ms
Iteration   3: 7.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.151 ±(99.9%) 5.078 ops/ms [Average]
  (min, avg, max) = (6.834, 7.151, 7.356), stdev = 0.278
  CI (99.9%): [2.073, 12.230] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.553 ops/ms
# Warmup Iteration   2: 6.809 ops/ms
# Warmup Iteration   3: 7.193 ops/ms
Iteration   1: 7.416 ops/ms
Iteration   2: 7.697 ops/ms
Iteration   3: 7.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.539 ±(99.9%) 2.613 ops/ms [Average]
  (min, avg, max) = (7.416, 7.539, 7.697), stdev = 0.143
  CI (99.9%): [4.926, 10.152] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.315 ops/ms
# Warmup Iteration   2: 6.644 ops/ms
# Warmup Iteration   3: 7.231 ops/ms
Iteration   1: 7.197 ops/ms
Iteration   2: 7.326 ops/ms
Iteration   3: 7.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.251 ±(99.9%) 1.217 ops/ms [Average]
  (min, avg, max) = (7.197, 7.251, 7.326), stdev = 0.067
  CI (99.9%): [6.034, 8.468] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.528 ops/ms
# Warmup Iteration   2: 5.168 ops/ms
# Warmup Iteration   3: 5.588 ops/ms
Iteration   1: 5.515 ops/ms
Iteration   2: 5.443 ops/ms
Iteration   3: 5.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.463 ±(99.9%) 0.821 ops/ms [Average]
  (min, avg, max) = (5.432, 5.463, 5.515), stdev = 0.045
  CI (99.9%): [4.643, 6.284] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.337 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.838 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.698 ±(99.9%) 0.005 ms/op
Iteration   1: 4.619 ±(99.9%) 0.004 ms/op
Iteration   2: 4.756 ±(99.9%) 0.004 ms/op
Iteration   3: 4.669 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.682 ±(99.9%) 1.267 ms/op [Average]
  (min, avg, max) = (4.619, 4.682, 4.756), stdev = 0.069
  CI (99.9%): [3.414, 5.949] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.873 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.859 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.676 ±(99.9%) 0.003 ms/op
Iteration   1: 4.553 ±(99.9%) 0.003 ms/op
Iteration   2: 4.540 ±(99.9%) 0.004 ms/op
Iteration   3: 4.347 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.480 ±(99.9%) 2.105 ms/op [Average]
  (min, avg, max) = (4.347, 4.480, 4.553), stdev = 0.115
  CI (99.9%): [2.375, 6.584] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.404 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.876 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.681 ±(99.9%) 0.004 ms/op
Iteration   1: 4.506 ±(99.9%) 0.003 ms/op
Iteration   2: 4.407 ±(99.9%) 0.005 ms/op
Iteration   3: 4.316 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.409 ±(99.9%) 1.732 ms/op [Average]
  (min, avg, max) = (4.316, 4.409, 4.506), stdev = 0.095
  CI (99.9%): [2.677, 6.142] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.694 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 6.042 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.675 ±(99.9%) 0.016 ms/op
Iteration   1: 5.575 ±(99.9%) 0.013 ms/op
Iteration   2: 5.542 ±(99.9%) 0.014 ms/op
Iteration   3: 5.460 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.526 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (5.460, 5.526, 5.575), stdev = 0.059
  CI (99.9%): [4.443, 6.608] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.743 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.911 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.530 ±(99.9%) 0.013 ms/op
Iteration   1: 4.512 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   4.383 ms/op
                 createUser·p0.90:   5.800 ms/op
                 createUser·p0.95:   6.308 ms/op
                 createUser·p0.99:   8.185 ms/op
                 createUser·p0.999:  14.411 ms/op
                 createUser·p0.9999: 17.921 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   2: 4.521 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.300 ms/op
                 createUser·p0.99:   7.856 ms/op
                 createUser·p0.999:  15.763 ms/op
                 createUser·p0.9999: 18.671 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   3: 4.657 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   4.571 ms/op
                 createUser·p0.90:   5.980 ms/op
                 createUser·p0.95:   6.406 ms/op
                 createUser·p0.99:   7.840 ms/op
                 createUser·p0.999:  13.730 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 210293
  mean =      4.562 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4275 
    [ 2.500,  5.000) = 142375 
    [ 5.000,  7.500) = 60659 
    [ 7.500, 10.000) = 2274 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      6.341 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     14.479 ms/op
     p(99.9900) =     21.132 ms/op
     p(99.9990) =     22.626 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 6.535 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.352 ±(99.9%) 0.014 ms/op
Iteration   1: 4.207 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   4.104 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   5.767 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  10.699 ms/op
                 existUser·p0.9999: 24.471 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   2: 4.271 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   4.153 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  12.177 ms/op
                 existUser·p0.9999: 27.362 ms/op
                 existUser·p1.00:   27.918 ms/op

Iteration   3: 4.209 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   4.108 ms/op
                 existUser·p0.90:   5.456 ms/op
                 existUser·p0.95:   5.890 ms/op
                 existUser·p0.99:   7.318 ms/op
                 existUser·p0.999:  11.781 ms/op
                 existUser·p0.9999: 26.536 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 226871
  mean =      4.229 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5248 
    [ 2.500,  5.000) = 180226 
    [ 5.000,  7.500) = 39609 
    [ 7.500, 10.000) = 1373 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     11.829 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     27.752 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.673 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.673 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.507 ±(99.9%) 0.014 ms/op
Iteration   1: 4.454 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.734 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   7.922 ms/op
                 getUser·p0.999:  13.322 ms/op
                 getUser·p0.9999: 16.265 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   2: 4.357 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.669 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   7.774 ms/op
                 getUser·p0.999:  14.117 ms/op
                 getUser·p0.9999: 22.020 ms/op
                 getUser·p1.00:   22.217 ms/op

Iteration   3: 4.398 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.669 ms/op
                 getUser·p0.95:   6.119 ms/op
                 getUser·p0.99:   7.537 ms/op
                 getUser·p0.999:  11.972 ms/op
                 getUser·p0.9999: 23.813 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217870
  mean =      4.403 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5752 
    [ 2.500,  5.000) = 157617 
    [ 5.000,  7.500) = 51875 
    [ 7.500, 10.000) = 2120 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.152 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     12.765 ms/op
     p(99.9900) =     23.043 ms/op
     p(99.9990) =     24.132 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.845 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.986 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.549 ±(99.9%) 0.021 ms/op
Iteration   1: 5.519 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   10.224 ms/op
                 listUser·p0.999:  15.285 ms/op
                 listUser·p0.9999: 18.265 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   2: 5.494 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.659 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   7.029 ms/op
                 listUser·p0.95:   7.946 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 20.885 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 5.494 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   10.977 ms/op
                 listUser·p0.999:  21.725 ms/op
                 listUser·p0.9999: 23.845 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174491
  mean =      5.502 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 167 
    [ 2.500,  5.000) = 70054 
    [ 5.000,  7.500) = 90505 
    [ 7.500, 10.000) = 11506 
    [10.000, 12.500) = 1535 
    [12.500, 15.000) = 287 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.086 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     23.075 ms/op
     p(99.9990) =     24.706 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.151 ± 5.078  ops/ms
ClientGrpc.existUser                       thrpt       3   7.539 ± 2.613  ops/ms
ClientGrpc.getUser                         thrpt       3   7.251 ± 1.217  ops/ms
ClientGrpc.listUser                        thrpt       3   5.463 ± 0.821  ops/ms
ClientGrpc.createUser                       avgt       3   4.682 ± 1.267   ms/op
ClientGrpc.existUser                        avgt       3   4.480 ± 2.105   ms/op
ClientGrpc.getUser                          avgt       3   4.409 ± 1.732   ms/op
ClientGrpc.listUser                         avgt       3   5.526 ± 1.083   ms/op
ClientGrpc.createUser                     sample  210293   4.562 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.044           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.882           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.341           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.971           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.479           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.132           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.774           ms/op
ClientGrpc.existUser                      sample  226871   4.229 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.855           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.390           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.833           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.193           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.829           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.575           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.918           ms/op
ClientGrpc.getUser                        sample  217870   4.403 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.029           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.693           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.152           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.750           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.765           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.043           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.281           ms/op
ClientGrpc.listUser                       sample  174491   5.502 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.010           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.086           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.453           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.923           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.075           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.756           ms/op
