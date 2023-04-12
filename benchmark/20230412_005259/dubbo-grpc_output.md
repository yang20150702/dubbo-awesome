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
# Warmup Iteration   1: 2.012 ops/ms
# Warmup Iteration   2: 5.045 ops/ms
# Warmup Iteration   3: 6.806 ops/ms
Iteration   1: 7.162 ops/ms
Iteration   2: 7.186 ops/ms
Iteration   3: 7.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.209 ±(99.9%) 1.114 ops/ms [Average]
  (min, avg, max) = (7.162, 7.209, 7.278), stdev = 0.061
  CI (99.9%): [6.094, 8.323] (assumes normal distribution)


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
# Warmup Iteration   1: 4.486 ops/ms
# Warmup Iteration   2: 6.535 ops/ms
# Warmup Iteration   3: 7.203 ops/ms
Iteration   1: 7.464 ops/ms
Iteration   2: 7.378 ops/ms
Iteration   3: 7.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.418 ±(99.9%) 0.789 ops/ms [Average]
  (min, avg, max) = (7.378, 7.418, 7.464), stdev = 0.043
  CI (99.9%): [6.630, 8.207] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ops/ms
# Warmup Iteration   2: 6.595 ops/ms
# Warmup Iteration   3: 6.902 ops/ms
Iteration   1: 7.185 ops/ms
Iteration   2: 7.278 ops/ms
Iteration   3: 7.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.244 ±(99.9%) 0.942 ops/ms [Average]
  (min, avg, max) = (7.185, 7.244, 7.278), stdev = 0.052
  CI (99.9%): [6.302, 8.187] (assumes normal distribution)


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
# Warmup Iteration   1: 3.509 ops/ms
# Warmup Iteration   2: 5.210 ops/ms
# Warmup Iteration   3: 5.583 ops/ms
Iteration   1: 5.755 ops/ms
Iteration   2: 5.665 ops/ms
Iteration   3: 5.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.690 ±(99.9%) 1.027 ops/ms [Average]
  (min, avg, max) = (5.651, 5.690, 5.755), stdev = 0.056
  CI (99.9%): [4.663, 6.718] (assumes normal distribution)


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
# Warmup Iteration   1: 7.582 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.923 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.718 ±(99.9%) 0.003 ms/op
Iteration   1: 4.547 ±(99.9%) 0.005 ms/op
Iteration   2: 4.578 ±(99.9%) 0.004 ms/op
Iteration   3: 4.420 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.515 ±(99.9%) 1.525 ms/op [Average]
  (min, avg, max) = (4.420, 4.515, 4.578), stdev = 0.084
  CI (99.9%): [2.990, 6.040] (assumes normal distribution)


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
# Warmup Iteration   1: 6.657 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.553 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.302 ±(99.9%) 0.004 ms/op
Iteration   1: 4.155 ±(99.9%) 0.005 ms/op
Iteration   2: 4.215 ±(99.9%) 0.004 ms/op
Iteration   3: 4.167 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.179 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (4.155, 4.179, 4.215), stdev = 0.032
  CI (99.9%): [3.601, 4.757] (assumes normal distribution)


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
# Warmup Iteration   1: 7.334 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 5.008 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.734 ±(99.9%) 0.004 ms/op
Iteration   1: 4.599 ±(99.9%) 0.005 ms/op
Iteration   2: 4.460 ±(99.9%) 0.015 ms/op
Iteration   3: 4.553 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.537 ±(99.9%) 1.294 ms/op [Average]
  (min, avg, max) = (4.460, 4.537, 4.599), stdev = 0.071
  CI (99.9%): [3.243, 5.831] (assumes normal distribution)


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
# Warmup Iteration   1: 8.981 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 6.200 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.749 ±(99.9%) 0.018 ms/op
Iteration   1: 5.618 ±(99.9%) 0.029 ms/op
Iteration   2: 5.584 ±(99.9%) 0.017 ms/op
Iteration   3: 5.671 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.624 ±(99.9%) 0.802 ms/op [Average]
  (min, avg, max) = (5.584, 5.624, 5.671), stdev = 0.044
  CI (99.9%): [4.822, 6.427] (assumes normal distribution)


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
# Warmup Iteration   1: 7.439 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.014 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.686 ±(99.9%) 0.017 ms/op
Iteration   1: 4.563 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.980 ms/op
                 createUser·p0.95:   6.791 ms/op
                 createUser·p0.99:   9.224 ms/op
                 createUser·p0.999:  12.403 ms/op
                 createUser·p0.9999: 15.352 ms/op
                 createUser·p1.00:   15.778 ms/op

Iteration   2: 4.579 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.915 ms/op
                 createUser·p0.95:   6.545 ms/op
                 createUser·p0.99:   8.315 ms/op
                 createUser·p0.999:  17.526 ms/op
                 createUser·p0.9999: 22.313 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   3: 4.585 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.833 ms/op
                 createUser·p0.95:   6.496 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  17.472 ms/op
                 createUser·p0.9999: 24.872 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 209917
  mean =      4.576 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5288 
    [ 2.500,  5.000) = 148186 
    [ 5.000,  7.500) = 51109 
    [ 7.500, 10.000) = 4394 
    [10.000, 12.500) = 638 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.906 ms/op
     p(95.0000) =      6.611 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     15.290 ms/op
     p(99.9900) =     23.628 ms/op
     p(99.9990) =     25.123 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 7.007 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.703 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.456 ±(99.9%) 0.016 ms/op
Iteration   1: 4.337 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   4.133 ms/op
                 existUser·p0.90:   5.538 ms/op
                 existUser·p0.95:   6.355 ms/op
                 existUser·p0.99:   8.520 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 15.815 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 4.285 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   4.092 ms/op
                 existUser·p0.90:   5.661 ms/op
                 existUser·p0.95:   6.496 ms/op
                 existUser·p0.99:   8.929 ms/op
                 existUser·p0.999:  14.718 ms/op
                 existUser·p0.9999: 19.908 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   3: 4.283 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   4.063 ms/op
                 existUser·p0.90:   5.661 ms/op
                 existUser·p0.95:   6.480 ms/op
                 existUser·p0.99:   8.897 ms/op
                 existUser·p0.999:  14.352 ms/op
                 existUser·p0.9999: 18.877 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 223048
  mean =      4.302 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8312 
    [ 2.500,  5.000) = 172690 
    [ 5.000,  7.500) = 36782 
    [ 7.500, 10.000) = 4121 
    [10.000, 12.500) = 669 
    [12.500, 15.000) = 329 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.447 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 7.117 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.290 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.016 ms/op
Iteration   1: 4.465 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.743 ms/op
                 getUser·p0.95:   6.480 ms/op
                 getUser·p0.99:   8.651 ms/op
                 getUser·p0.999:  15.037 ms/op
                 getUser·p0.9999: 17.788 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   2: 4.587 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.972 ms/op
                 getUser·p0.95:   6.840 ms/op
                 getUser·p0.99:   9.240 ms/op
                 getUser·p0.999:  14.079 ms/op
                 getUser·p0.9999: 22.743 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   3: 4.458 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.644 ms/op
                 getUser·p0.95:   6.480 ms/op
                 getUser·p0.99:   8.380 ms/op
                 getUser·p0.999:  13.931 ms/op
                 getUser·p0.9999: 20.507 ms/op
                 getUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213040
  mean =      4.503 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4469 
    [ 2.500,  5.000) = 159534 
    [ 5.000,  7.500) = 43860 
    [ 7.500, 10.000) = 4289 
    [10.000, 12.500) = 551 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.792 ms/op
     p(95.0000) =      6.603 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     14.188 ms/op
     p(99.9900) =     21.191 ms/op
     p(99.9990) =     23.187 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 8.503 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.166 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.703 ±(99.9%) 0.027 ms/op
Iteration   1: 5.837 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.595 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   8.233 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  18.448 ms/op
                 listUser·p0.9999: 25.531 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 5.620 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   7.897 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  26.184 ms/op
                 listUser·p0.9999: 29.950 ms/op
                 listUser·p1.00:   30.278 ms/op

Iteration   3: 5.639 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   7.684 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.567 ms/op
                 listUser·p0.999:  21.175 ms/op
                 listUser·p0.9999: 36.349 ms/op
                 listUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168525
  mean =      5.697 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 175 
    [ 2.500,  5.000) = 67575 
    [ 5.000,  7.500) = 78663 
    [ 7.500, 10.000) = 17402 
    [10.000, 12.500) = 3536 
    [12.500, 15.000) = 653 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      7.954 ms/op
     p(95.0000) =      9.044 ms/op
     p(99.0000) =     11.829 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     30.053 ms/op
     p(99.9990) =     37.311 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.209 ± 1.114  ops/ms
ClientGrpc.existUser                       thrpt       3   7.418 ± 0.789  ops/ms
ClientGrpc.getUser                         thrpt       3   7.244 ± 0.942  ops/ms
ClientGrpc.listUser                        thrpt       3   5.690 ± 1.027  ops/ms
ClientGrpc.createUser                       avgt       3   4.515 ± 1.525   ms/op
ClientGrpc.existUser                        avgt       3   4.179 ± 0.578   ms/op
ClientGrpc.getUser                          avgt       3   4.537 ± 1.294   ms/op
ClientGrpc.listUser                         avgt       3   5.624 ± 0.802   ms/op
ClientGrpc.createUser                     sample  209917   4.576 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.167           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.906           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.611           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.749           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.290           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.628           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.231           ms/op
ClientGrpc.existUser                      sample  223048   4.302 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.939           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.096           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.620           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.447           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.782           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.057           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.235           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.349           ms/op
ClientGrpc.getUser                        sample  213040   4.503 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.102           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.792           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.603           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.765           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.188           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.191           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.396           ms/op
ClientGrpc.listUser                       sample  168525   5.697 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.563           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.259           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.954           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.044           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.829           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.135           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.053           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.356           ms/op
