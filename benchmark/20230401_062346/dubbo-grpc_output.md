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
# Warmup Iteration   1: 3.436 ops/ms
# Warmup Iteration   2: 7.314 ops/ms
# Warmup Iteration   3: 8.406 ops/ms
Iteration   1: 8.866 ops/ms
Iteration   2: 8.894 ops/ms
Iteration   3: 8.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.886 ±(99.9%) 0.305 ops/ms [Average]
  (min, avg, max) = (8.866, 8.886, 8.897), stdev = 0.017
  CI (99.9%): [8.581, 9.190] (assumes normal distribution)


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
# Warmup Iteration   1: 6.645 ops/ms
# Warmup Iteration   2: 8.764 ops/ms
# Warmup Iteration   3: 9.272 ops/ms
Iteration   1: 9.348 ops/ms
Iteration   2: 9.602 ops/ms
Iteration   3: 9.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.427 ±(99.9%) 2.776 ops/ms [Average]
  (min, avg, max) = (9.330, 9.427, 9.602), stdev = 0.152
  CI (99.9%): [6.651, 12.203] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.589 ops/ms
# Warmup Iteration   2: 7.963 ops/ms
# Warmup Iteration   3: 8.777 ops/ms
Iteration   1: 8.953 ops/ms
Iteration   2: 9.092 ops/ms
Iteration   3: 9.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.042 ±(99.9%) 1.405 ops/ms [Average]
  (min, avg, max) = (8.953, 9.042, 9.092), stdev = 0.077
  CI (99.9%): [7.637, 10.447] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.439 ops/ms
# Warmup Iteration   2: 6.462 ops/ms
# Warmup Iteration   3: 6.640 ops/ms
Iteration   1: 6.865 ops/ms
Iteration   2: 6.828 ops/ms
Iteration   3: 6.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.811 ±(99.9%) 1.167 ops/ms [Average]
  (min, avg, max) = (6.740, 6.811, 6.865), stdev = 0.064
  CI (99.9%): [5.644, 7.978] (assumes normal distribution)


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
# Warmup Iteration   1: 5.354 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.017 ms/op
Iteration   1: 3.584 ±(99.9%) 0.003 ms/op
Iteration   2: 3.543 ±(99.9%) 0.003 ms/op
Iteration   3: 3.575 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.567 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (3.543, 3.567, 3.584), stdev = 0.021
  CI (99.9%): [3.178, 3.957] (assumes normal distribution)


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
# Warmup Iteration   1: 4.890 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.002 ms/op
Iteration   1: 3.431 ±(99.9%) 0.004 ms/op
Iteration   2: 3.428 ±(99.9%) 0.003 ms/op
Iteration   3: 3.366 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.408 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (3.366, 3.408, 3.431), stdev = 0.037
  CI (99.9%): [2.742, 4.074] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.433 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.005 ms/op
Iteration   1: 3.539 ±(99.9%) 0.005 ms/op
Iteration   2: 3.575 ±(99.9%) 0.005 ms/op
Iteration   3: 3.582 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.565 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (3.539, 3.565, 3.582), stdev = 0.023
  CI (99.9%): [3.147, 3.984] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.227 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.016 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.722 ±(99.9%) 0.012 ms/op
Iteration   1: 4.662 ±(99.9%) 0.012 ms/op
Iteration   2: 4.526 ±(99.9%) 0.012 ms/op
Iteration   3: 4.639 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.609 ±(99.9%) 1.334 ms/op [Average]
  (min, avg, max) = (4.526, 4.609, 4.662), stdev = 0.073
  CI (99.9%): [3.275, 5.943] (assumes normal distribution)


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
# Warmup Iteration   1: 5.219 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.009 ms/op
Iteration   1: 3.568 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  8.080 ms/op
                 createUser·p0.9999: 14.699 ms/op
                 createUser·p1.00:   15.221 ms/op

Iteration   2: 3.567 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   4.989 ms/op
                 createUser·p0.999:  12.255 ms/op
                 createUser·p0.9999: 15.272 ms/op
                 createUser·p1.00:   16.646 ms/op

Iteration   3: 3.568 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  15.106 ms/op
                 createUser·p0.9999: 32.279 ms/op
                 createUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 268943
  mean =      3.568 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4973 
    [ 2.500,  5.000) = 260233 
    [ 5.000,  7.500) = 3204 
    [ 7.500, 10.000) = 238 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     11.059 ms/op
     p(99.9900) =     31.599 ms/op
     p(99.9990) =     32.778 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


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
# Warmup Iteration   1: 4.843 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.007 ms/op
Iteration   1: 3.433 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.043 ms/op
                 existUser·p0.999:  10.516 ms/op
                 existUser·p0.9999: 14.479 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   2: 3.385 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  7.152 ms/op
                 existUser·p0.9999: 15.002 ms/op
                 existUser·p1.00:   16.433 ms/op

Iteration   3: 3.573 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  13.377 ms/op
                 existUser·p0.9999: 28.806 ms/op
                 existUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277152
  mean =      3.462 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6692 
    [ 2.500,  5.000) = 267316 
    [ 5.000,  7.500) = 2553 
    [ 7.500, 10.000) = 324 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =      9.795 ms/op
     p(99.9900) =     27.666 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 5.258 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.008 ms/op
Iteration   1: 3.648 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   5.885 ms/op
                 getUser·p0.999:  8.312 ms/op
                 getUser·p0.9999: 15.011 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   2: 3.616 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  9.105 ms/op
                 getUser·p0.9999: 18.121 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   3: 3.623 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  8.094 ms/op
                 getUser·p0.9999: 17.727 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 264343
  mean =      3.629 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 7826 
    [ 2.500,  3.750) = 158498 
    [ 3.750,  5.000) = 91732 
    [ 5.000,  6.250) = 4590 
    [ 6.250,  7.500) = 880 
    [ 7.500,  8.750) = 430 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     17.844 ms/op
     p(99.9990) =     19.782 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 5.873 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.964 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.802 ±(99.9%) 0.015 ms/op
Iteration   1: 4.591 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.710 ms/op
                 listUser·p0.95:   6.676 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  19.005 ms/op
                 listUser·p0.9999: 38.339 ms/op
                 listUser·p1.00:   39.191 ms/op

Iteration   2: 4.737 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  22.807 ms/op
                 listUser·p0.9999: 26.861 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   3: 4.673 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.545 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  18.726 ms/op
                 listUser·p0.9999: 21.823 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205712
  mean =      4.666 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 654 
    [ 2.500,  5.000) = 163562 
    [ 5.000,  7.500) = 36752 
    [ 7.500, 10.000) = 4221 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      6.578 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     37.683 ms/op
     p(99.9990) =     38.986 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.886 ± 0.305  ops/ms
ClientGrpc.existUser                       thrpt       3   9.427 ± 2.776  ops/ms
ClientGrpc.getUser                         thrpt       3   9.042 ± 1.405  ops/ms
ClientGrpc.listUser                        thrpt       3   6.811 ± 1.167  ops/ms
ClientGrpc.createUser                       avgt       3   3.567 ± 0.390   ms/op
ClientGrpc.existUser                        avgt       3   3.408 ± 0.666   ms/op
ClientGrpc.getUser                          avgt       3   3.565 ± 0.419   ms/op
ClientGrpc.listUser                         avgt       3   4.609 ± 1.334   ms/op
ClientGrpc.createUser                     sample  268943   3.568 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.856           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.104           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.059           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.599           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.866           ms/op
ClientGrpc.existUser                      sample  277152   3.462 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.869           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.120           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.795           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.666           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.179           ms/op
ClientGrpc.getUser                        sample  264343   3.629 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.748           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.743           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.421           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.844           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.890           ms/op
ClientGrpc.listUser                       sample  205712   4.666 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.949           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.241           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.333           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          37.683           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.191           ms/op
