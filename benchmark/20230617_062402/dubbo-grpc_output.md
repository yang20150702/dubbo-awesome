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
# Warmup Iteration   1: 2.034 ops/ms
# Warmup Iteration   2: 4.386 ops/ms
# Warmup Iteration   3: 6.624 ops/ms
Iteration   1: 6.975 ops/ms
Iteration   2: 7.268 ops/ms
Iteration   3: 7.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.124 ±(99.9%) 2.678 ops/ms [Average]
  (min, avg, max) = (6.975, 7.124, 7.268), stdev = 0.147
  CI (99.9%): [4.446, 9.802] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.368 ops/ms
# Warmup Iteration   2: 6.863 ops/ms
# Warmup Iteration   3: 7.444 ops/ms
Iteration   1: 7.554 ops/ms
Iteration   2: 7.654 ops/ms
Iteration   3: 7.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.646 ±(99.9%) 1.605 ops/ms [Average]
  (min, avg, max) = (7.554, 7.646, 7.729), stdev = 0.088
  CI (99.9%): [6.041, 9.251] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.987 ops/ms
# Warmup Iteration   2: 6.489 ops/ms
# Warmup Iteration   3: 6.964 ops/ms
Iteration   1: 7.218 ops/ms
Iteration   2: 7.085 ops/ms
Iteration   3: 7.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.128 ±(99.9%) 1.421 ops/ms [Average]
  (min, avg, max) = (7.081, 7.128, 7.218), stdev = 0.078
  CI (99.9%): [5.706, 8.549] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.288 ops/ms
# Warmup Iteration   2: 5.000 ops/ms
# Warmup Iteration   3: 5.493 ops/ms
Iteration   1: 5.599 ops/ms
Iteration   2: 5.470 ops/ms
Iteration   3: 5.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.549 ±(99.9%) 1.258 ops/ms [Average]
  (min, avg, max) = (5.470, 5.549, 5.599), stdev = 0.069
  CI (99.9%): [4.290, 6.807] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.087 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.809 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.445 ±(99.9%) 0.018 ms/op
Iteration   1: 4.466 ±(99.9%) 0.004 ms/op
Iteration   2: 4.428 ±(99.9%) 0.004 ms/op
Iteration   3: 4.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.446 ±(99.9%) 0.350 ms/op [Average]
  (min, avg, max) = (4.428, 4.446, 4.466), stdev = 0.019
  CI (99.9%): [4.096, 4.795] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.486 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.696 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.354 ±(99.9%) 0.007 ms/op
Iteration   1: 4.350 ±(99.9%) 0.002 ms/op
Iteration   2: 4.299 ±(99.9%) 0.004 ms/op
Iteration   3: 4.340 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.330 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (4.299, 4.330, 4.350), stdev = 0.027
  CI (99.9%): [3.835, 4.824] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.011 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.973 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.693 ±(99.9%) 0.006 ms/op
Iteration   1: 4.651 ±(99.9%) 0.005 ms/op
Iteration   2: 4.469 ±(99.9%) 0.004 ms/op
Iteration   3: 4.520 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.546 ±(99.9%) 1.714 ms/op [Average]
  (min, avg, max) = (4.469, 4.546, 4.651), stdev = 0.094
  CI (99.9%): [2.833, 6.260] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.774 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 6.226 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.769 ±(99.9%) 0.021 ms/op
Iteration   1: 5.587 ±(99.9%) 0.016 ms/op
Iteration   2: 5.766 ±(99.9%) 0.022 ms/op
Iteration   3: 5.546 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.633 ±(99.9%) 2.136 ms/op [Average]
  (min, avg, max) = (5.546, 5.633, 5.766), stdev = 0.117
  CI (99.9%): [3.497, 7.769] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.033 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.911 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.574 ±(99.9%) 0.018 ms/op
Iteration   1: 4.560 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.784 ms/op
                 createUser·p0.95:   6.341 ms/op
                 createUser·p0.99:   8.364 ms/op
                 createUser·p0.999:  12.841 ms/op
                 createUser·p0.9999: 28.835 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   2: 4.459 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.652 ms/op
                 createUser·p0.95:   6.185 ms/op
                 createUser·p0.99:   8.166 ms/op
                 createUser·p0.999:  17.635 ms/op
                 createUser·p0.9999: 29.506 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   3: 4.504 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.587 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   8.167 ms/op
                 createUser·p0.999:  12.960 ms/op
                 createUser·p0.9999: 29.357 ms/op
                 createUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 212911
  mean =      4.507 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4093 
    [ 2.500,  5.000) = 157616 
    [ 5.000,  7.500) = 47858 
    [ 7.500, 10.000) = 2599 
    [10.000, 12.500) = 462 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     13.191 ms/op
     p(99.9900) =     29.196 ms/op
     p(99.9990) =     29.872 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.587 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.719 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.423 ±(99.9%) 0.014 ms/op
Iteration   1: 4.452 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   4.284 ms/op
                 existUser·p0.90:   5.620 ms/op
                 existUser·p0.95:   6.283 ms/op
                 existUser·p0.99:   8.503 ms/op
                 existUser·p0.999:  14.818 ms/op
                 existUser·p0.9999: 17.867 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   2: 4.349 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   4.202 ms/op
                 existUser·p0.90:   5.431 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   7.775 ms/op
                 existUser·p0.999:  10.804 ms/op
                 existUser·p0.9999: 30.221 ms/op
                 existUser·p1.00:   30.736 ms/op

Iteration   3: 4.246 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   4.141 ms/op
                 existUser·p0.90:   5.423 ms/op
                 existUser·p0.95:   5.997 ms/op
                 existUser·p0.99:   7.823 ms/op
                 existUser·p0.999:  12.610 ms/op
                 existUser·p0.9999: 23.755 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 220785
  mean =      4.347 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5718 
    [ 2.500,  5.000) = 173213 
    [ 5.000,  7.500) = 38676 
    [ 7.500, 10.000) = 2525 
    [10.000, 12.500) = 436 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     29.554 ms/op
     p(99.9990) =     30.631 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.389 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.912 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.015 ms/op
Iteration   1: 4.605 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   5.784 ms/op
                 getUser·p0.95:   6.332 ms/op
                 getUser·p0.99:   8.172 ms/op
                 getUser·p0.999:  12.492 ms/op
                 getUser·p0.9999: 18.355 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   2: 4.597 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.784 ms/op
                 getUser·p0.95:   6.324 ms/op
                 getUser·p0.99:   8.880 ms/op
                 getUser·p0.999:  14.201 ms/op
                 getUser·p0.9999: 19.238 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   3: 4.557 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.767 ms/op
                 getUser·p0.95:   6.382 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  12.072 ms/op
                 getUser·p0.9999: 22.708 ms/op
                 getUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 209362
  mean =      4.586 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3834 
    [ 2.500,  5.000) = 148745 
    [ 5.000,  7.500) = 53051 
    [ 7.500, 10.000) = 2948 
    [10.000, 12.500) = 569 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.784 ms/op
     p(95.0000) =      6.349 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     12.581 ms/op
     p(99.9900) =     19.696 ms/op
     p(99.9990) =     23.420 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.003 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 6.839 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.819 ±(99.9%) 0.025 ms/op
Iteration   1: 5.827 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   5.472 ms/op
                 listUser·p0.90:   7.791 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.551 ms/op
                 listUser·p0.999:  21.038 ms/op
                 listUser·p0.9999: 29.229 ms/op
                 listUser·p1.00:   32.571 ms/op

Iteration   2: 5.722 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   5.390 ms/op
                 listUser·p0.90:   7.668 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  25.776 ms/op
                 listUser·p0.9999: 28.901 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   3: 5.755 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  24.164 ms/op
                 listUser·p0.9999: 27.972 ms/op
                 listUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166480
  mean =      5.768 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 121 
    [ 2.500,  5.000) = 53160 
    [ 5.000,  7.500) = 94371 
    [ 7.500, 10.000) = 15484 
    [10.000, 12.500) = 2590 
    [12.500, 15.000) = 437 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      7.692 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     11.092 ms/op
     p(99.9000) =     24.069 ms/op
     p(99.9900) =     28.610 ms/op
     p(99.9990) =     32.354 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.124 ± 2.678  ops/ms
ClientGrpc.existUser                       thrpt       3   7.646 ± 1.605  ops/ms
ClientGrpc.getUser                         thrpt       3   7.128 ± 1.421  ops/ms
ClientGrpc.listUser                        thrpt       3   5.549 ± 1.258  ops/ms
ClientGrpc.createUser                       avgt       3   4.446 ± 0.350   ms/op
ClientGrpc.existUser                        avgt       3   4.330 ± 0.494   ms/op
ClientGrpc.getUser                          avgt       3   4.546 ± 1.714   ms/op
ClientGrpc.listUser                         avgt       3   5.633 ± 2.136   ms/op
ClientGrpc.createUser                     sample  212911   4.507 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.063           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.677           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.218           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.225           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.191           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.196           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.573           ms/op
ClientGrpc.existUser                      sample  220785   4.347 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.092           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.497           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.062           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.036           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.452           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.554           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.736           ms/op
ClientGrpc.getUser                        sample  209362   4.586 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.133           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.784           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.349           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.471           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.581           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.696           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.527           ms/op
ClientGrpc.listUser                       sample  166480   5.768 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.411           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.692           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.092           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          24.069           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.610           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.571           ms/op
