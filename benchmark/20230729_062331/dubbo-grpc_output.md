# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.008 ops/ms
# Warmup Iteration   2: 4.360 ops/ms
# Warmup Iteration   3: 6.535 ops/ms
Iteration   1: 6.639 ops/ms
Iteration   2: 6.692 ops/ms
Iteration   3: 6.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.724 ±(99.9%) 1.908 ops/ms [Average]
  (min, avg, max) = (6.639, 6.724, 6.841), stdev = 0.105
  CI (99.9%): [4.816, 8.632] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.237 ops/ms
# Warmup Iteration   2: 6.705 ops/ms
# Warmup Iteration   3: 7.154 ops/ms
Iteration   1: 7.417 ops/ms
Iteration   2: 7.557 ops/ms
Iteration   3: 7.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.511 ±(99.9%) 1.474 ops/ms [Average]
  (min, avg, max) = (7.417, 7.511, 7.558), stdev = 0.081
  CI (99.9%): [6.036, 8.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.868 ops/ms
# Warmup Iteration   2: 6.139 ops/ms
# Warmup Iteration   3: 6.676 ops/ms
Iteration   1: 6.771 ops/ms
Iteration   2: 6.862 ops/ms
Iteration   3: 7.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.882 ±(99.9%) 2.220 ops/ms [Average]
  (min, avg, max) = (6.771, 6.882, 7.012), stdev = 0.122
  CI (99.9%): [4.662, 9.102] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.345 ops/ms
# Warmup Iteration   2: 4.537 ops/ms
# Warmup Iteration   3: 5.288 ops/ms
Iteration   1: 5.338 ops/ms
Iteration   2: 5.345 ops/ms
Iteration   3: 5.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.346 ±(99.9%) 0.165 ops/ms [Average]
  (min, avg, max) = (5.338, 5.346, 5.356), stdev = 0.009
  CI (99.9%): [5.181, 5.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.924 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.034 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.810 ±(99.9%) 0.013 ms/op
Iteration   1: 4.601 ±(99.9%) 0.004 ms/op
Iteration   2: 4.679 ±(99.9%) 0.004 ms/op
Iteration   3: 4.734 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.672 ±(99.9%) 1.221 ms/op [Average]
  (min, avg, max) = (4.601, 4.672, 4.734), stdev = 0.067
  CI (99.9%): [3.451, 5.893] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.856 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.837 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.446 ±(99.9%) 0.004 ms/op
Iteration   1: 4.496 ±(99.9%) 0.004 ms/op
Iteration   2: 4.526 ±(99.9%) 0.004 ms/op
Iteration   3: 4.599 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.540 ±(99.9%) 0.961 ms/op [Average]
  (min, avg, max) = (4.496, 4.540, 4.599), stdev = 0.053
  CI (99.9%): [3.579, 5.502] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.961 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.124 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.729 ±(99.9%) 0.021 ms/op
Iteration   1: 4.705 ±(99.9%) 0.003 ms/op
Iteration   2: 4.724 ±(99.9%) 0.004 ms/op
Iteration   3: 4.576 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.668 ±(99.9%) 1.464 ms/op [Average]
  (min, avg, max) = (4.576, 4.668, 4.724), stdev = 0.080
  CI (99.9%): [3.204, 6.132] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.588 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.643 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 6.022 ±(99.9%) 0.017 ms/op
Iteration   1: 5.961 ±(99.9%) 0.014 ms/op
Iteration   2: 5.933 ±(99.9%) 0.016 ms/op
Iteration   3: 5.903 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.932 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (5.903, 5.932, 5.961), stdev = 0.029
  CI (99.9%): [5.406, 6.459] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.608 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 4.937 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.633 ±(99.9%) 0.013 ms/op
Iteration   1: 4.575 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.661 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   8.217 ms/op
                 createUser·p0.999:  13.984 ms/op
                 createUser·p0.9999: 16.188 ms/op
                 createUser·p1.00:   16.761 ms/op

Iteration   2: 4.480 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   5.865 ms/op
                 createUser·p0.99:   7.651 ms/op
                 createUser·p0.999:  13.402 ms/op
                 createUser·p0.9999: 19.001 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   3: 4.529 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   5.923 ms/op
                 createUser·p0.99:   7.455 ms/op
                 createUser·p0.999:  11.960 ms/op
                 createUser·p0.9999: 21.721 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 211908
  mean =      4.528 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3192 
    [ 2.500,  5.000) = 159302 
    [ 5.000,  7.500) = 46921 
    [ 7.500, 10.000) = 1737 
    [10.000, 12.500) = 465 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     13.435 ms/op
     p(99.9900) =     20.048 ms/op
     p(99.9990) =     21.914 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.696 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.705 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.012 ms/op
Iteration   1: 4.235 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   4.125 ms/op
                 existUser·p0.90:   5.251 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   7.576 ms/op
                 existUser·p0.999:  12.229 ms/op
                 existUser·p0.9999: 16.216 ms/op
                 existUser·p1.00:   16.761 ms/op

Iteration   2: 4.316 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   5.276 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  11.171 ms/op
                 existUser·p0.9999: 19.011 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   3: 4.219 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   4.129 ms/op
                 existUser·p0.90:   5.120 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   6.988 ms/op
                 existUser·p0.999:  12.531 ms/op
                 existUser·p0.9999: 20.954 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 225594
  mean =      4.256 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5101 
    [ 2.500,  5.000) = 189418 
    [ 5.000,  7.500) = 29393 
    [ 7.500, 10.000) = 1117 
    [10.000, 12.500) = 395 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      4.153 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     12.009 ms/op
     p(99.9900) =     19.096 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.243 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.051 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.666 ±(99.9%) 0.014 ms/op
Iteration   1: 4.683 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   5.825 ms/op
                 getUser·p0.95:   6.341 ms/op
                 getUser·p0.99:   8.217 ms/op
                 getUser·p0.999:  13.093 ms/op
                 getUser·p0.9999: 18.618 ms/op
                 getUser·p1.00:   18.973 ms/op

Iteration   2: 4.701 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   5.775 ms/op
                 getUser·p0.95:   6.267 ms/op
                 getUser·p0.99:   8.995 ms/op
                 getUser·p0.999:  13.672 ms/op
                 getUser·p0.9999: 20.427 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   3: 4.734 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   6.291 ms/op
                 getUser·p0.99:   8.320 ms/op
                 getUser·p0.999:  12.434 ms/op
                 getUser·p0.9999: 21.365 ms/op
                 getUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 203907
  mean =      4.706 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2541 
    [ 2.500,  5.000) = 139508 
    [ 5.000,  7.500) = 58572 
    [ 7.500, 10.000) = 2263 
    [10.000, 12.500) = 760 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.300 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     12.945 ms/op
     p(99.9900) =     20.434 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.470 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 7.315 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.417 ±(99.9%) 0.023 ms/op
Iteration   1: 6.273 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   5.939 ms/op
                 listUser·p0.90:   8.241 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   11.403 ms/op
                 listUser·p0.999:  19.782 ms/op
                 listUser·p0.9999: 24.355 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 6.374 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.958 ms/op
                 listUser·p0.50:   6.029 ms/op
                 listUser·p0.90:   8.290 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   12.124 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 22.151 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   3: 6.008 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   8.053 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   11.910 ms/op
                 listUser·p0.999:  22.996 ms/op
                 listUser·p0.9999: 26.369 ms/op
                 listUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 154458
  mean =      6.214 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 25968 
    [ 5.000,  7.500) = 104827 
    [ 7.500, 10.000) = 19237 
    [10.000, 12.500) = 3306 
    [12.500, 15.000) = 632 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      5.882 ms/op
     p(90.0000) =      8.200 ms/op
     p(95.0000) =      9.191 ms/op
     p(99.0000) =     11.796 ms/op
     p(99.9000) =     21.415 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     27.979 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.724 ± 1.908  ops/ms
ClientGrpc.existUser                       thrpt       3   7.511 ± 1.474  ops/ms
ClientGrpc.getUser                         thrpt       3   6.882 ± 2.220  ops/ms
ClientGrpc.listUser                        thrpt       3   5.346 ± 0.165  ops/ms
ClientGrpc.createUser                       avgt       3   4.672 ± 1.221   ms/op
ClientGrpc.existUser                        avgt       3   4.540 ± 0.961   ms/op
ClientGrpc.getUser                          avgt       3   4.668 ± 1.464   ms/op
ClientGrpc.listUser                         avgt       3   5.932 ± 0.527   ms/op
ClientGrpc.createUser                     sample  211908   4.528 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.929           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.546           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.980           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.758           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.435           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.048           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  225594   4.256 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.969           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.218           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.669           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.062           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.009           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.096           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.234           ms/op
ClientGrpc.getUser                        sample  203907   4.706 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.116           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.300           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.536           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.945           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.434           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.529           ms/op
ClientGrpc.listUser                       sample  154458   6.214 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.528           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.200           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.191           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.796           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.415           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.559           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.443           ms/op
