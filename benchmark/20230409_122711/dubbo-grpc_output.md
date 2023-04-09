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
# Warmup Iteration   1: 2.226 ops/ms
# Warmup Iteration   2: 5.253 ops/ms
# Warmup Iteration   3: 6.801 ops/ms
Iteration   1: 7.252 ops/ms
Iteration   2: 7.280 ops/ms
Iteration   3: 7.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.277 ±(99.9%) 0.427 ops/ms [Average]
  (min, avg, max) = (7.252, 7.277, 7.299), stdev = 0.023
  CI (99.9%): [6.850, 7.704] (assumes normal distribution)


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
# Warmup Iteration   1: 4.474 ops/ms
# Warmup Iteration   2: 7.185 ops/ms
# Warmup Iteration   3: 7.607 ops/ms
Iteration   1: 7.731 ops/ms
Iteration   2: 7.984 ops/ms
Iteration   3: 7.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.820 ±(99.9%) 2.589 ops/ms [Average]
  (min, avg, max) = (7.731, 7.820, 7.984), stdev = 0.142
  CI (99.9%): [5.231, 10.409] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.342 ops/ms
# Warmup Iteration   2: 6.493 ops/ms
# Warmup Iteration   3: 7.120 ops/ms
Iteration   1: 7.210 ops/ms
Iteration   2: 7.103 ops/ms
Iteration   3: 7.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.171 ±(99.9%) 1.080 ops/ms [Average]
  (min, avg, max) = (7.103, 7.171, 7.210), stdev = 0.059
  CI (99.9%): [6.090, 8.251] (assumes normal distribution)


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
# Warmup Iteration   1: 3.764 ops/ms
# Warmup Iteration   2: 4.927 ops/ms
# Warmup Iteration   3: 5.561 ops/ms
Iteration   1: 5.519 ops/ms
Iteration   2: 5.499 ops/ms
Iteration   3: 5.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.499 ±(99.9%) 0.373 ops/ms [Average]
  (min, avg, max) = (5.479, 5.499, 5.519), stdev = 0.020
  CI (99.9%): [5.126, 5.873] (assumes normal distribution)


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
# Warmup Iteration   1: 6.434 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.860 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.564 ±(99.9%) 0.007 ms/op
Iteration   1: 4.575 ±(99.9%) 0.004 ms/op
Iteration   2: 4.407 ±(99.9%) 0.004 ms/op
Iteration   3: 4.492 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.491 ±(99.9%) 1.534 ms/op [Average]
  (min, avg, max) = (4.407, 4.491, 4.575), stdev = 0.084
  CI (99.9%): [2.957, 6.026] (assumes normal distribution)


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
# Warmup Iteration   1: 6.101 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.457 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.347 ±(99.9%) 0.004 ms/op
Iteration   1: 4.043 ±(99.9%) 0.004 ms/op
Iteration   2: 4.273 ±(99.9%) 0.004 ms/op
Iteration   3: 4.211 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.176 ±(99.9%) 2.176 ms/op [Average]
  (min, avg, max) = (4.043, 4.176, 4.273), stdev = 0.119
  CI (99.9%): [1.999, 6.352] (assumes normal distribution)


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
# Warmup Iteration   1: 6.544 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.634 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.508 ±(99.9%) 0.004 ms/op
Iteration   1: 4.283 ±(99.9%) 0.003 ms/op
Iteration   2: 4.327 ±(99.9%) 0.004 ms/op
Iteration   3: 4.362 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.324 ±(99.9%) 0.718 ms/op [Average]
  (min, avg, max) = (4.283, 4.324, 4.362), stdev = 0.039
  CI (99.9%): [3.606, 5.042] (assumes normal distribution)


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
# Warmup Iteration   1: 8.777 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.371 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.859 ±(99.9%) 0.012 ms/op
Iteration   1: 5.720 ±(99.9%) 0.009 ms/op
Iteration   2: 6.072 ±(99.9%) 0.024 ms/op
Iteration   3: 5.789 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.860 ±(99.9%) 3.401 ms/op [Average]
  (min, avg, max) = (5.720, 5.860, 6.072), stdev = 0.186
  CI (99.9%): [2.460, 9.261] (assumes normal distribution)


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
# Warmup Iteration   1: 7.097 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 4.733 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.511 ±(99.9%) 0.013 ms/op
Iteration   1: 4.523 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   4.366 ms/op
                 createUser·p0.90:   5.726 ms/op
                 createUser·p0.95:   6.250 ms/op
                 createUser·p0.99:   8.053 ms/op
                 createUser·p0.999:  14.018 ms/op
                 createUser·p0.9999: 18.471 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   2: 4.435 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.587 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   7.700 ms/op
                 createUser·p0.999:  20.244 ms/op
                 createUser·p0.9999: 25.756 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 4.346 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.489 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   7.987 ms/op
                 createUser·p0.999:  11.276 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216484
  mean =      4.434 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4209 
    [ 2.500,  5.000) = 165446 
    [ 5.000,  7.500) = 43804 
    [ 7.500, 10.000) = 2450 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     13.378 ms/op
     p(99.9900) =     25.472 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 6.852 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.013 ms/op
Iteration   1: 4.329 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.221 ms/op
                 existUser·p0.50:   4.178 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   8.045 ms/op
                 existUser·p0.999:  15.649 ms/op
                 existUser·p0.9999: 20.577 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   2: 4.220 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.292 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   7.479 ms/op
                 existUser·p0.999:  11.518 ms/op
                 existUser·p0.9999: 22.081 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 4.222 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   4.100 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.800 ms/op
                 existUser·p0.99:   7.496 ms/op
                 existUser·p0.999:  15.085 ms/op
                 existUser·p0.9999: 30.160 ms/op
                 existUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 225417
  mean =      4.256 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4829 
    [ 2.500,  5.000) = 185054 
    [ 5.000,  7.500) = 33025 
    [ 7.500, 10.000) = 1831 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      4.121 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     14.374 ms/op
     p(99.9900) =     27.293 ms/op
     p(99.9990) =     30.409 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 6.932 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.690 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.544 ±(99.9%) 0.015 ms/op
Iteration   1: 4.379 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.358 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.954 ms/op
                 getUser·p0.999:  13.173 ms/op
                 getUser·p0.9999: 17.596 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   2: 4.470 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.118 ms/op
                 getUser·p0.99:   7.660 ms/op
                 getUser·p0.999:  12.967 ms/op
                 getUser·p0.9999: 18.940 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   3: 4.370 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.025 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   7.963 ms/op
                 getUser·p0.999:  13.774 ms/op
                 getUser·p0.9999: 21.682 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217910
  mean =      4.406 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2723 
    [ 2.500,  5.000) = 172535 
    [ 5.000,  7.500) = 39706 
    [ 7.500, 10.000) = 2225 
    [10.000, 12.500) = 424 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     20.985 ms/op
     p(99.9990) =     22.068 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 8.424 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 6.139 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.800 ±(99.9%) 0.023 ms/op
Iteration   1: 5.628 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.348 ms/op
                 listUser·p0.95:   8.241 ms/op
                 listUser·p0.99:   10.444 ms/op
                 listUser·p0.999:  16.632 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 5.580 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.447 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.764 ms/op
                 listUser·p0.999:  20.799 ms/op
                 listUser·p0.9999: 27.805 ms/op
                 listUser·p1.00:   28.246 ms/op

Iteration   3: 5.594 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.332 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   10.469 ms/op
                 listUser·p0.999:  21.094 ms/op
                 listUser·p0.9999: 26.978 ms/op
                 listUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171416
  mean =      5.601 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 139 
    [ 2.500,  5.000) = 63477 
    [ 5.000,  7.500) = 92256 
    [ 7.500, 10.000) = 12987 
    [10.000, 12.500) = 2007 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      7.373 ms/op
     p(95.0000) =      8.290 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     18.861 ms/op
     p(99.9900) =     27.286 ms/op
     p(99.9990) =     30.559 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.277 ± 0.427  ops/ms
ClientGrpc.existUser                       thrpt       3   7.820 ± 2.589  ops/ms
ClientGrpc.getUser                         thrpt       3   7.171 ± 1.080  ops/ms
ClientGrpc.listUser                        thrpt       3   5.499 ± 0.373  ops/ms
ClientGrpc.createUser                       avgt       3   4.491 ± 1.534   ms/op
ClientGrpc.existUser                        avgt       3   4.176 ± 2.176   ms/op
ClientGrpc.getUser                          avgt       3   4.324 ± 0.718   ms/op
ClientGrpc.listUser                         avgt       3   5.860 ± 3.401   ms/op
ClientGrpc.createUser                     sample  216484   4.434 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.628           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.177           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.913           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.378           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.472           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.821           ms/op
ClientGrpc.existUser                      sample  225417   4.256 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.956           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.121           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.308           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.841           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.684           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.374           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.293           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.507           ms/op
ClientGrpc.getUser                        sample  217910   4.406 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.024           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.497           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.095           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.873           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.238           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.985           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.905           ms/op
ClientGrpc.listUser                       sample  171416   5.601 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.884           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.292           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.290           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.584           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.861           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.286           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.899           ms/op
