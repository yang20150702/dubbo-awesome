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
# Warmup Iteration   1: 3.014 ops/ms
# Warmup Iteration   2: 6.918 ops/ms
# Warmup Iteration   3: 7.912 ops/ms
Iteration   1: 8.267 ops/ms
Iteration   2: 8.462 ops/ms
Iteration   3: 8.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.417 ±(99.9%) 2.429 ops/ms [Average]
  (min, avg, max) = (8.267, 8.417, 8.522), stdev = 0.133
  CI (99.9%): [5.988, 10.846] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.405 ops/ms
# Warmup Iteration   2: 8.336 ops/ms
# Warmup Iteration   3: 8.935 ops/ms
Iteration   1: 8.736 ops/ms
Iteration   2: 8.948 ops/ms
Iteration   3: 9.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.927 ±(99.9%) 3.315 ops/ms [Average]
  (min, avg, max) = (8.736, 8.927, 9.097), stdev = 0.182
  CI (99.9%): [5.612, 12.242] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.528 ops/ms
# Warmup Iteration   2: 8.128 ops/ms
# Warmup Iteration   3: 8.376 ops/ms
Iteration   1: 8.485 ops/ms
Iteration   2: 8.286 ops/ms
Iteration   3: 8.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.444 ±(99.9%) 2.590 ops/ms [Average]
  (min, avg, max) = (8.286, 8.444, 8.561), stdev = 0.142
  CI (99.9%): [5.854, 11.034] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.506 ops/ms
# Warmup Iteration   2: 6.101 ops/ms
# Warmup Iteration   3: 6.600 ops/ms
Iteration   1: 6.434 ops/ms
Iteration   2: 6.640 ops/ms
Iteration   3: 6.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.627 ±(99.9%) 3.405 ops/ms [Average]
  (min, avg, max) = (6.434, 6.627, 6.807), stdev = 0.187
  CI (99.9%): [3.222, 10.032] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.283 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.004 ms/op
Iteration   1: 3.807 ±(99.9%) 0.002 ms/op
Iteration   2: 3.985 ±(99.9%) 0.003 ms/op
Iteration   3: 3.820 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.871 ±(99.9%) 1.817 ms/op [Average]
  (min, avg, max) = (3.807, 3.871, 3.985), stdev = 0.100
  CI (99.9%): [2.054, 5.687] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.863 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.005 ms/op
Iteration   1: 3.540 ±(99.9%) 0.003 ms/op
Iteration   2: 3.524 ±(99.9%) 0.003 ms/op
Iteration   3: 3.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.506 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (3.453, 3.506, 3.540), stdev = 0.046
  CI (99.9%): [2.661, 4.350] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.345 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.002 ms/op
Iteration   1: 3.943 ±(99.9%) 0.004 ms/op
Iteration   2: 3.755 ±(99.9%) 0.003 ms/op
Iteration   3: 3.812 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.837 ±(99.9%) 1.758 ms/op [Average]
  (min, avg, max) = (3.755, 3.837, 3.943), stdev = 0.096
  CI (99.9%): [2.079, 5.595] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.956 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.290 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.817 ±(99.9%) 0.010 ms/op
Iteration   1: 4.971 ±(99.9%) 0.020 ms/op
Iteration   2: 5.032 ±(99.9%) 0.009 ms/op
Iteration   3: 4.817 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.940 ±(99.9%) 2.017 ms/op [Average]
  (min, avg, max) = (4.817, 4.940, 5.032), stdev = 0.111
  CI (99.9%): [2.923, 6.957] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.405 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.012 ms/op
Iteration   1: 3.908 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   7.758 ms/op
                 createUser·p0.999:  12.622 ms/op
                 createUser·p0.9999: 17.546 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   2: 3.863 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   6.943 ms/op
                 createUser·p0.999:  10.736 ms/op
                 createUser·p0.9999: 18.898 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   3: 4.010 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.352 ms/op
                 createUser·p0.99:   7.373 ms/op
                 createUser·p0.999:  14.125 ms/op
                 createUser·p0.9999: 21.923 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 244336
  mean =      3.926 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6660 
    [ 2.500,  5.000) = 218530 
    [ 5.000,  7.500) = 16830 
    [ 7.500, 10.000) = 1740 
    [10.000, 12.500) = 353 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      7.403 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     21.023 ms/op
     p(99.9990) =     22.075 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.347 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.011 ms/op
Iteration   1: 3.575 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  9.601 ms/op
                 existUser·p0.9999: 22.186 ms/op
                 existUser·p1.00:   22.413 ms/op

Iteration   2: 3.637 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.947 ms/op
                 existUser·p0.999:  13.960 ms/op
                 existUser·p0.9999: 18.816 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   3: 3.565 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  10.753 ms/op
                 existUser·p0.9999: 19.104 ms/op
                 existUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267080
  mean =      3.592 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9044 
    [ 2.500,  5.000) = 248988 
    [ 5.000,  7.500) = 7507 
    [ 7.500, 10.000) = 1102 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     12.122 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     22.359 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 5.026 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.011 ms/op
Iteration   1: 3.908 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  14.099 ms/op
                 getUser·p0.9999: 20.021 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   2: 3.957 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   7.307 ms/op
                 getUser·p0.999:  10.093 ms/op
                 getUser·p0.9999: 19.101 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   3: 3.864 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   6.794 ms/op
                 getUser·p0.999:  11.821 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 245462
  mean =      3.909 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6961 
    [ 2.500,  5.000) = 219512 
    [ 5.000,  7.500) = 17025 
    [ 7.500, 10.000) = 1634 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     11.053 ms/op
     p(99.9900) =     22.264 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 7.394 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.343 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.870 ±(99.9%) 0.019 ms/op
Iteration   1: 5.027 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.587 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.734 ms/op
                 listUser·p0.95:   7.512 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  16.987 ms/op
                 listUser·p0.9999: 19.045 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 4.962 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.562 ms/op
                 listUser·p0.95:   7.422 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  16.393 ms/op
                 listUser·p0.9999: 20.269 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   3: 4.890 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  26.404 ms/op
                 listUser·p0.9999: 36.599 ms/op
                 listUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 193440
  mean =      4.959 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 454 
    [ 2.500,  5.000) = 127343 
    [ 5.000,  7.500) = 57224 
    [ 7.500, 10.000) = 6872 
    [10.000, 12.500) = 911 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.521 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     18.434 ms/op
     p(99.9900) =     35.236 ms/op
     p(99.9990) =     37.290 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.417 ± 2.429  ops/ms
ClientGrpc.existUser                       thrpt       3   8.927 ± 3.315  ops/ms
ClientGrpc.getUser                         thrpt       3   8.444 ± 2.590  ops/ms
ClientGrpc.listUser                        thrpt       3   6.627 ± 3.405  ops/ms
ClientGrpc.createUser                       avgt       3   3.871 ± 1.817   ms/op
ClientGrpc.existUser                        avgt       3   3.506 ± 0.844   ms/op
ClientGrpc.getUser                          avgt       3   3.837 ± 1.758   ms/op
ClientGrpc.listUser                         avgt       3   4.940 ± 2.017   ms/op
ClientGrpc.createUser                     sample  244336   3.926 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.893           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.841           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.317           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.403           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.255           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.023           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.217           ms/op
ClientGrpc.existUser                      sample  267080   3.592 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.521           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.710           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.439           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.122           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.382           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.413           ms/op
ClientGrpc.getUser                        sample  245462   3.909 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.042           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.308           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.184           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.053           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.264           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  193440   4.959 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.990           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.521           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.340           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.667           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.434           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.236           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.290           ms/op
