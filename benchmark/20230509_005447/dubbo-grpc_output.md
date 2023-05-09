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
# Warmup Iteration   1: 2.215 ops/ms
# Warmup Iteration   2: 5.335 ops/ms
# Warmup Iteration   3: 6.811 ops/ms
Iteration   1: 7.345 ops/ms
Iteration   2: 7.295 ops/ms
Iteration   3: 7.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.346 ±(99.9%) 0.937 ops/ms [Average]
  (min, avg, max) = (7.295, 7.346, 7.397), stdev = 0.051
  CI (99.9%): [6.408, 8.283] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.841 ops/ms
# Warmup Iteration   2: 7.192 ops/ms
# Warmup Iteration   3: 7.809 ops/ms
Iteration   1: 7.748 ops/ms
Iteration   2: 7.807 ops/ms
Iteration   3: 7.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.822 ±(99.9%) 1.516 ops/ms [Average]
  (min, avg, max) = (7.748, 7.822, 7.912), stdev = 0.083
  CI (99.9%): [6.306, 9.339] (assumes normal distribution)


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
# Warmup Iteration   1: 4.194 ops/ms
# Warmup Iteration   2: 6.970 ops/ms
# Warmup Iteration   3: 7.368 ops/ms
Iteration   1: 7.408 ops/ms
Iteration   2: 7.571 ops/ms
Iteration   3: 7.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.552 ±(99.9%) 2.475 ops/ms [Average]
  (min, avg, max) = (7.408, 7.552, 7.677), stdev = 0.136
  CI (99.9%): [5.077, 10.027] (assumes normal distribution)


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
# Warmup Iteration   1: 3.774 ops/ms
# Warmup Iteration   2: 4.859 ops/ms
# Warmup Iteration   3: 5.694 ops/ms
Iteration   1: 5.745 ops/ms
Iteration   2: 5.679 ops/ms
Iteration   3: 5.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.729 ±(99.9%) 0.811 ops/ms [Average]
  (min, avg, max) = (5.679, 5.729, 5.763), stdev = 0.044
  CI (99.9%): [4.918, 6.540] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.496 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.498 ±(99.9%) 0.010 ms/op
Iteration   1: 4.414 ±(99.9%) 0.004 ms/op
Iteration   2: 4.334 ±(99.9%) 0.003 ms/op
Iteration   3: 4.439 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.396 ±(99.9%) 0.999 ms/op [Average]
  (min, avg, max) = (4.334, 4.396, 4.439), stdev = 0.055
  CI (99.9%): [3.397, 5.395] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.516 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.539 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.168 ±(99.9%) 0.004 ms/op
Iteration   1: 4.027 ±(99.9%) 0.003 ms/op
Iteration   2: 4.199 ±(99.9%) 0.003 ms/op
Iteration   3: 4.167 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.131 ±(99.9%) 1.663 ms/op [Average]
  (min, avg, max) = (4.027, 4.131, 4.199), stdev = 0.091
  CI (99.9%): [2.468, 5.794] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.811 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.678 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.397 ±(99.9%) 0.005 ms/op
Iteration   1: 4.398 ±(99.9%) 0.004 ms/op
Iteration   2: 4.416 ±(99.9%) 0.004 ms/op
Iteration   3: 4.379 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.398 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (4.379, 4.398, 4.416), stdev = 0.018
  CI (99.9%): [4.063, 4.732] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.658 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.695 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.713 ±(99.9%) 0.020 ms/op
Iteration   1: 5.746 ±(99.9%) 0.033 ms/op
Iteration   2: 5.821 ±(99.9%) 0.021 ms/op
Iteration   3: 5.898 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.822 ±(99.9%) 1.384 ms/op [Average]
  (min, avg, max) = (5.746, 5.822, 5.898), stdev = 0.076
  CI (99.9%): [4.438, 7.206] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.345 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 4.821 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.598 ±(99.9%) 0.015 ms/op
Iteration   1: 4.369 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   6.111 ms/op
                 createUser·p0.99:   8.012 ms/op
                 createUser·p0.999:  12.611 ms/op
                 createUser·p0.9999: 16.696 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   2: 4.565 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   5.767 ms/op
                 createUser·p0.95:   6.316 ms/op
                 createUser·p0.99:   8.434 ms/op
                 createUser·p0.999:  13.724 ms/op
                 createUser·p0.9999: 18.940 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   3: 4.395 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   4.252 ms/op
                 createUser·p0.90:   5.505 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   8.651 ms/op
                 createUser·p0.999:  18.579 ms/op
                 createUser·p0.9999: 22.830 ms/op
                 createUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216247
  mean =      4.441 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6101 
    [ 2.500,  5.000) = 161538 
    [ 5.000,  7.500) = 45007 
    [ 7.500, 10.000) = 2619 
    [10.000, 12.500) = 609 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.160 ms/op
     p(99.0000) =      8.307 ms/op
     p(99.9000) =     14.688 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     22.867 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 6.665 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.440 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.013 ms/op
Iteration   1: 4.256 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   4.104 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   5.825 ms/op
                 existUser·p0.99:   7.922 ms/op
                 existUser·p0.999:  11.909 ms/op
                 existUser·p0.9999: 16.039 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   2: 4.202 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.218 ms/op
                 existUser·p0.95:   5.702 ms/op
                 existUser·p0.99:   7.651 ms/op
                 existUser·p0.999:  10.699 ms/op
                 existUser·p0.9999: 24.771 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   3: 4.133 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   4.022 ms/op
                 existUser·p0.90:   5.169 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   7.471 ms/op
                 existUser·p0.999:  12.157 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 228709
  mean =      4.197 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6330 
    [ 2.500,  5.000) = 189643 
    [ 5.000,  7.500) = 30167 
    [ 7.500, 10.000) = 1957 
    [10.000, 12.500) = 449 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     11.605 ms/op
     p(99.9900) =     22.618 ms/op
     p(99.9990) =     25.138 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 6.575 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.533 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.389 ±(99.9%) 0.013 ms/op
Iteration   1: 4.316 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   4.190 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.956 ms/op
                 getUser·p0.99:   8.225 ms/op
                 getUser·p0.999:  12.730 ms/op
                 getUser·p0.9999: 18.028 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   2: 4.329 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.489 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   7.897 ms/op
                 getUser·p0.999:  12.929 ms/op
                 getUser·p0.9999: 20.303 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   3: 4.345 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   4.182 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   5.988 ms/op
                 getUser·p0.99:   8.159 ms/op
                 getUser·p0.999:  12.440 ms/op
                 getUser·p0.9999: 35.998 ms/op
                 getUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221568
  mean =      4.330 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6449 
    [ 2.500,  5.000) = 175582 
    [ 5.000,  7.500) = 36466 
    [ 7.500, 10.000) = 2290 
    [10.000, 12.500) = 530 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     12.861 ms/op
     p(99.9900) =     35.248 ms/op
     p(99.9990) =     36.868 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


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
# Warmup Iteration   1: 8.788 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.174 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.842 ±(99.9%) 0.024 ms/op
Iteration   1: 5.774 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.621 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 23.116 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   2: 5.750 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.823 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   11.220 ms/op
                 listUser·p0.999:  20.870 ms/op
                 listUser·p0.9999: 24.838 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   3: 5.767 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.919 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  19.777 ms/op
                 listUser·p0.9999: 38.827 ms/op
                 listUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166531
  mean =      5.764 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 146 
    [ 2.500,  5.000) = 54510 
    [ 5.000,  7.500) = 92415 
    [ 7.500, 10.000) = 15887 
    [10.000, 12.500) = 2520 
    [12.500, 15.000) = 544 
    [15.000, 17.500) = 227 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.750 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     38.207 ms/op
     p(99.9990) =     39.147 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.346 ± 0.937  ops/ms
ClientGrpc.existUser                       thrpt       3   7.822 ± 1.516  ops/ms
ClientGrpc.getUser                         thrpt       3   7.552 ± 2.475  ops/ms
ClientGrpc.listUser                        thrpt       3   5.729 ± 0.811  ops/ms
ClientGrpc.createUser                       avgt       3   4.396 ± 0.999   ms/op
ClientGrpc.existUser                        avgt       3   4.131 ± 1.663   ms/op
ClientGrpc.getUser                          avgt       3   4.398 ± 0.334   ms/op
ClientGrpc.listUser                         avgt       3   5.822 ± 1.384   ms/op
ClientGrpc.createUser                     sample  216247   4.441 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.765           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.628           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.160           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.307           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.688           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.741           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.265           ms/op
ClientGrpc.existUser                      sample  228709   4.197 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.855           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.243           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.726           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.709           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.605           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.618           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.297           ms/op
ClientGrpc.getUser                        sample  221568   4.330 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.964           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.448           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.988           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.086           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.861           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.248           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.962           ms/op
ClientGrpc.listUser                       sample  166531   5.764 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.339           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.750           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.765           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.272           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.595           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          38.207           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.191           ms/op
