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
# Warmup Iteration   1: 2.071 ops/ms
# Warmup Iteration   2: 5.281 ops/ms
# Warmup Iteration   3: 6.207 ops/ms
Iteration   1: 6.576 ops/ms
Iteration   2: 6.796 ops/ms
Iteration   3: 6.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.687 ±(99.9%) 2.006 ops/ms [Average]
  (min, avg, max) = (6.576, 6.687, 6.796), stdev = 0.110
  CI (99.9%): [4.681, 8.693] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.522 ops/ms
# Warmup Iteration   2: 6.647 ops/ms
# Warmup Iteration   3: 6.962 ops/ms
Iteration   1: 6.953 ops/ms
Iteration   2: 7.022 ops/ms
Iteration   3: 7.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.125 ±(99.9%) 4.406 ops/ms [Average]
  (min, avg, max) = (6.953, 7.125, 7.401), stdev = 0.241
  CI (99.9%): [2.720, 11.531] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.367 ops/ms
# Warmup Iteration   2: 6.000 ops/ms
# Warmup Iteration   3: 6.466 ops/ms
Iteration   1: 6.431 ops/ms
Iteration   2: 6.331 ops/ms
Iteration   3: 6.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.409 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (6.331, 6.409, 6.465), stdev = 0.070
  CI (99.9%): [5.136, 7.681] (assumes normal distribution)


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
# Warmup Iteration   1: 3.103 ops/ms
# Warmup Iteration   2: 4.640 ops/ms
# Warmup Iteration   3: 5.241 ops/ms
Iteration   1: 5.332 ops/ms
Iteration   2: 5.432 ops/ms
Iteration   3: 5.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.377 ±(99.9%) 0.919 ops/ms [Average]
  (min, avg, max) = (5.332, 5.377, 5.432), stdev = 0.050
  CI (99.9%): [4.459, 6.296] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.837 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.069 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.922 ±(99.9%) 0.016 ms/op
Iteration   1: 4.940 ±(99.9%) 0.005 ms/op
Iteration   2: 4.928 ±(99.9%) 0.004 ms/op
Iteration   3: 4.914 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.928 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (4.914, 4.928, 4.940), stdev = 0.013
  CI (99.9%): [4.688, 5.167] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.033 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.999 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.724 ±(99.9%) 0.003 ms/op
Iteration   1: 4.628 ±(99.9%) 0.004 ms/op
Iteration   2: 4.683 ±(99.9%) 0.004 ms/op
Iteration   3: 4.794 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.701 ±(99.9%) 1.544 ms/op [Average]
  (min, avg, max) = (4.628, 4.701, 4.794), stdev = 0.085
  CI (99.9%): [3.157, 6.246] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.973 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.200 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 5.206 ±(99.9%) 0.005 ms/op
Iteration   1: 4.849 ±(99.9%) 0.005 ms/op
Iteration   2: 4.765 ±(99.9%) 0.006 ms/op
Iteration   3: 4.898 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.837 ±(99.9%) 1.229 ms/op [Average]
  (min, avg, max) = (4.765, 4.837, 4.898), stdev = 0.067
  CI (99.9%): [3.609, 6.066] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.785 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 7.042 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 6.223 ±(99.9%) 0.016 ms/op
Iteration   1: 6.117 ±(99.9%) 0.021 ms/op
Iteration   2: 6.162 ±(99.9%) 0.014 ms/op
Iteration   3: 6.103 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.128 ±(99.9%) 0.563 ms/op [Average]
  (min, avg, max) = (6.103, 6.128, 6.162), stdev = 0.031
  CI (99.9%): [5.565, 6.690] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.615 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.073 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.001 ±(99.9%) 0.019 ms/op
Iteration   1: 4.733 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   4.563 ms/op
                 createUser·p0.90:   5.956 ms/op
                 createUser·p0.95:   6.570 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  24.099 ms/op
                 createUser·p0.9999: 30.744 ms/op
                 createUser·p1.00:   31.064 ms/op

Iteration   2: 4.684 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   4.538 ms/op
                 createUser·p0.90:   5.939 ms/op
                 createUser·p0.95:   6.504 ms/op
                 createUser·p0.99:   8.331 ms/op
                 createUser·p0.999:  13.261 ms/op
                 createUser·p0.9999: 35.652 ms/op
                 createUser·p1.00:   36.241 ms/op

Iteration   3: 4.826 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   4.653 ms/op
                 createUser·p0.90:   6.095 ms/op
                 createUser·p0.95:   6.636 ms/op
                 createUser·p0.99:   8.569 ms/op
                 createUser·p0.999:  15.172 ms/op
                 createUser·p0.9999: 39.387 ms/op
                 createUser·p1.00:   39.649 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 202176
  mean =      4.747 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2335 
    [ 2.500,  5.000) = 132965 
    [ 5.000,  7.500) = 62540 
    [ 7.500, 10.000) = 3474 
    [10.000, 12.500) = 535 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.005 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     17.361 ms/op
     p(99.9900) =     39.242 ms/op
     p(99.9990) =     39.451 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


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
# Warmup Iteration   1: 6.916 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.933 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.622 ±(99.9%) 0.014 ms/op
Iteration   1: 4.576 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.759 ms/op
                 existUser·p0.95:   6.439 ms/op
                 existUser·p0.99:   8.536 ms/op
                 existUser·p0.999:  14.500 ms/op
                 existUser·p0.9999: 20.546 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 4.553 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   4.415 ms/op
                 existUser·p0.90:   5.923 ms/op
                 existUser·p0.95:   6.488 ms/op
                 existUser·p0.99:   8.700 ms/op
                 existUser·p0.999:  12.481 ms/op
                 existUser·p0.9999: 19.420 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   3: 4.489 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.767 ms/op
                 existUser·p0.95:   6.218 ms/op
                 existUser·p0.99:   8.045 ms/op
                 existUser·p0.999:  11.558 ms/op
                 existUser·p0.9999: 20.316 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 211481
  mean =      4.539 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5632 
    [ 2.500,  5.000) = 147682 
    [ 5.000,  7.500) = 54035 
    [ 7.500, 10.000) = 3381 
    [10.000, 12.500) = 476 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      6.382 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     13.361 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 7.477 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.598 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.955 ±(99.9%) 0.017 ms/op
Iteration   1: 4.747 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   4.628 ms/op
                 getUser·p0.90:   6.087 ms/op
                 getUser·p0.95:   6.619 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  13.040 ms/op
                 getUser·p0.9999: 20.906 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   2: 4.697 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   5.915 ms/op
                 getUser·p0.95:   6.406 ms/op
                 getUser·p0.99:   8.116 ms/op
                 getUser·p0.999:  11.600 ms/op
                 getUser·p0.9999: 19.743 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   3: 4.833 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   4.735 ms/op
                 getUser·p0.90:   6.054 ms/op
                 getUser·p0.95:   6.578 ms/op
                 getUser·p0.99:   8.355 ms/op
                 getUser·p0.999:  10.744 ms/op
                 getUser·p0.9999: 18.781 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 201701
  mean =      4.758 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4278 
    [ 2.500,  5.000) = 122698 
    [ 5.000,  7.500) = 70730 
    [ 7.500, 10.000) = 3347 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     11.719 ms/op
     p(99.9900) =     19.721 ms/op
     p(99.9990) =     21.165 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 9.665 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 7.519 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.246 ±(99.9%) 0.028 ms/op
Iteration   1: 6.230 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   8.618 ms/op
                 listUser·p0.95:   9.683 ms/op
                 listUser·p0.99:   12.599 ms/op
                 listUser·p0.999:  18.612 ms/op
                 listUser·p0.9999: 23.351 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   2: 6.397 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   5.956 ms/op
                 listUser·p0.90:   8.700 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   12.403 ms/op
                 listUser·p0.999:  16.727 ms/op
                 listUser·p0.9999: 25.952 ms/op
                 listUser·p1.00:   26.378 ms/op

Iteration   3: 6.130 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   8.290 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  30.499 ms/op
                 listUser·p0.9999: 36.540 ms/op
                 listUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 153661
  mean =      6.251 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 33789 
    [ 5.000,  7.500) = 90908 
    [ 7.500, 10.000) = 23315 
    [10.000, 12.500) = 4280 
    [12.500, 15.000) = 864 
    [15.000, 17.500) = 241 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      5.825 ms/op
     p(90.0000) =      8.536 ms/op
     p(95.0000) =      9.535 ms/op
     p(99.0000) =     12.222 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     35.628 ms/op
     p(99.9990) =     36.922 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.687 ± 2.006  ops/ms
ClientGrpc.existUser                       thrpt       3   7.125 ± 4.406  ops/ms
ClientGrpc.getUser                         thrpt       3   6.409 ± 1.273  ops/ms
ClientGrpc.listUser                        thrpt       3   5.377 ± 0.919  ops/ms
ClientGrpc.createUser                       avgt       3   4.928 ± 0.239   ms/op
ClientGrpc.existUser                        avgt       3   4.701 ± 1.544   ms/op
ClientGrpc.getUser                          avgt       3   4.837 ± 1.229   ms/op
ClientGrpc.listUser                         avgt       3   6.128 ± 0.563   ms/op
ClientGrpc.createUser                     sample  202176   4.747 ± 0.010   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.079           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.005           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.570           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.520           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          17.361           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          39.242           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          39.649           ms/op
ClientGrpc.existUser                      sample  211481   4.539 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.624           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.816           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.382           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.421           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.361           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.316           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.708           ms/op
ClientGrpc.getUser                        sample  201701   4.758 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.163           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.661           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.021           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.537           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.405           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.719           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.721           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.201           ms/op
ClientGrpc.listUser                       sample  153661   6.251 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.343           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.536           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.535           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.222           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.678           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.628           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.028           ms/op
