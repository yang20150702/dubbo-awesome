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
# Warmup Iteration   1: 2.173 ops/ms
# Warmup Iteration   2: 4.958 ops/ms
# Warmup Iteration   3: 6.972 ops/ms
Iteration   1: 7.094 ops/ms
Iteration   2: 6.993 ops/ms
Iteration   3: 7.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.142 ±(99.9%) 3.252 ops/ms [Average]
  (min, avg, max) = (6.993, 7.142, 7.340), stdev = 0.178
  CI (99.9%): [3.890, 10.394] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.419 ops/ms
# Warmup Iteration   2: 7.306 ops/ms
# Warmup Iteration   3: 7.747 ops/ms
Iteration   1: 7.511 ops/ms
Iteration   2: 7.746 ops/ms
Iteration   3: 7.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.649 ±(99.9%) 2.237 ops/ms [Average]
  (min, avg, max) = (7.511, 7.649, 7.746), stdev = 0.123
  CI (99.9%): [5.411, 9.886] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.170 ops/ms
# Warmup Iteration   2: 6.641 ops/ms
# Warmup Iteration   3: 7.038 ops/ms
Iteration   1: 7.292 ops/ms
Iteration   2: 7.229 ops/ms
Iteration   3: 7.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.233 ±(99.9%) 1.043 ops/ms [Average]
  (min, avg, max) = (7.178, 7.233, 7.292), stdev = 0.057
  CI (99.9%): [6.190, 8.275] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.783 ops/ms
# Warmup Iteration   2: 4.916 ops/ms
# Warmup Iteration   3: 5.634 ops/ms
Iteration   1: 5.614 ops/ms
Iteration   2: 5.633 ops/ms
Iteration   3: 5.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.632 ±(99.9%) 0.328 ops/ms [Average]
  (min, avg, max) = (5.614, 5.632, 5.650), stdev = 0.018
  CI (99.9%): [5.304, 5.960] (assumes normal distribution)


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
# Warmup Iteration   1: 6.979 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.768 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.561 ±(99.9%) 0.010 ms/op
Iteration   1: 4.384 ±(99.9%) 0.003 ms/op
Iteration   2: 4.418 ±(99.9%) 0.004 ms/op
Iteration   3: 4.434 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.412 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (4.384, 4.412, 4.434), stdev = 0.025
  CI (99.9%): [3.950, 4.874] (assumes normal distribution)


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
# Warmup Iteration   1: 6.758 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.002 ms/op
Iteration   1: 4.107 ±(99.9%) 0.002 ms/op
Iteration   2: 4.109 ±(99.9%) 0.002 ms/op
Iteration   3: 4.050 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.089 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (4.050, 4.089, 4.109), stdev = 0.034
  CI (99.9%): [3.474, 4.703] (assumes normal distribution)


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
# Warmup Iteration   1: 6.335 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.702 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.426 ±(99.9%) 0.003 ms/op
Iteration   1: 4.453 ±(99.9%) 0.007 ms/op
Iteration   2: 4.344 ±(99.9%) 0.006 ms/op
Iteration   3: 4.346 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.381 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (4.344, 4.381, 4.453), stdev = 0.062
  CI (99.9%): [3.250, 5.513] (assumes normal distribution)


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
# Warmup Iteration   1: 8.545 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 6.046 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.690 ±(99.9%) 0.014 ms/op
Iteration   1: 5.470 ±(99.9%) 0.012 ms/op
Iteration   2: 5.529 ±(99.9%) 0.025 ms/op
Iteration   3: 5.574 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.525 ±(99.9%) 0.952 ms/op [Average]
  (min, avg, max) = (5.470, 5.525, 5.574), stdev = 0.052
  CI (99.9%): [4.573, 6.477] (assumes normal distribution)


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
# Warmup Iteration   1: 6.869 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.857 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.515 ±(99.9%) 0.013 ms/op
Iteration   1: 4.490 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   7.386 ms/op
                 createUser·p0.999:  15.295 ms/op
                 createUser·p0.9999: 26.116 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   2: 4.470 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   7.186 ms/op
                 createUser·p0.999:  12.730 ms/op
                 createUser·p0.9999: 20.546 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   3: 4.358 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.259 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  16.456 ms/op
                 createUser·p0.9999: 22.085 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216209
  mean =      4.439 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2895 
    [ 2.500,  5.000) = 172300 
    [ 5.000,  7.500) = 39130 
    [ 7.500, 10.000) = 1143 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.208 ms/op
     p(99.9000) =     14.988 ms/op
     p(99.9900) =     24.888 ms/op
     p(99.9990) =     26.209 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.454 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.319 ±(99.9%) 0.011 ms/op
Iteration   1: 4.275 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   4.182 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  11.691 ms/op
                 existUser·p0.9999: 16.860 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   2: 4.177 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   4.088 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  10.424 ms/op
                 existUser·p0.9999: 16.521 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   3: 4.089 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   4.026 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  12.698 ms/op
                 existUser·p0.9999: 21.201 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229752
  mean =      4.179 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3826 
    [ 2.500,  5.000) = 200552 
    [ 5.000,  7.500) = 24108 
    [ 7.500, 10.000) = 811 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     19.533 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 6.282 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.844 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.410 ±(99.9%) 0.012 ms/op
Iteration   1: 4.304 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.218 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  10.691 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   2: 4.431 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  13.173 ms/op
                 getUser·p0.9999: 24.464 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   3: 4.269 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.005 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  13.471 ms/op
                 getUser·p0.9999: 24.875 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221311
  mean =      4.333 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3606 
    [ 2.500,  5.000) = 184572 
    [ 5.000,  7.500) = 31782 
    [ 7.500, 10.000) = 999 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     11.447 ms/op
     p(99.9900) =     24.272 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 9.508 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 6.164 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.588 ±(99.9%) 0.019 ms/op
Iteration   1: 5.544 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.021 ms/op
                 listUser·p0.95:   8.016 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  15.259 ms/op
                 listUser·p0.9999: 23.958 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   2: 5.743 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   5.472 ms/op
                 listUser·p0.90:   7.332 ms/op
                 listUser·p0.95:   8.208 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  19.355 ms/op
                 listUser·p0.9999: 25.723 ms/op
                 listUser·p1.00:   27.329 ms/op

Iteration   3: 5.659 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   8.094 ms/op
                 listUser·p0.99:   10.633 ms/op
                 listUser·p0.999:  19.284 ms/op
                 listUser·p0.9999: 31.295 ms/op
                 listUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169862
  mean =      5.647 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 158 
    [ 2.500,  5.000) = 51664 
    [ 5.000,  7.500) = 104526 
    [ 7.500, 10.000) = 11440 
    [10.000, 12.500) = 1451 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.193 ms/op
     p(95.0000) =      8.110 ms/op
     p(99.0000) =     10.306 ms/op
     p(99.9000) =     18.813 ms/op
     p(99.9900) =     29.330 ms/op
     p(99.9990) =     31.670 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.142 ± 3.252  ops/ms
ClientGrpc.existUser                       thrpt       3   7.649 ± 2.237  ops/ms
ClientGrpc.getUser                         thrpt       3   7.233 ± 1.043  ops/ms
ClientGrpc.listUser                        thrpt       3   5.632 ± 0.328  ops/ms
ClientGrpc.createUser                       avgt       3   4.412 ± 0.462   ms/op
ClientGrpc.existUser                        avgt       3   4.089 ± 0.614   ms/op
ClientGrpc.getUser                          avgt       3   4.381 ± 1.132   ms/op
ClientGrpc.listUser                         avgt       3   5.525 ± 0.952   ms/op
ClientGrpc.createUser                     sample  216209   4.439 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.092           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.431           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.849           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.208           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.988           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.888           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.214           ms/op
ClientGrpc.existUser                      sample  229752   4.179 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.881           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.096           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.054           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.407           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.480           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.255           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.533           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.234           ms/op
ClientGrpc.getUser                        sample  221311   4.333 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.856           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.235           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.693           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.906           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.447           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.272           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.887           ms/op
ClientGrpc.listUser                       sample  169862   5.647 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.341           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.193           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.110           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.306           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.813           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.330           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.785           ms/op
