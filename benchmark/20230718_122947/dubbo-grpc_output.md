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
# Warmup Iteration   1: 3.736 ops/ms
# Warmup Iteration   2: 8.619 ops/ms
# Warmup Iteration   3: 9.722 ops/ms
Iteration   1: 10.135 ops/ms
Iteration   2: 10.164 ops/ms
Iteration   3: 10.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.121 ±(99.9%) 0.959 ops/ms [Average]
  (min, avg, max) = (10.062, 10.121, 10.164), stdev = 0.053
  CI (99.9%): [9.162, 11.079] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.815 ops/ms
# Warmup Iteration   2: 10.328 ops/ms
# Warmup Iteration   3: 10.652 ops/ms
Iteration   1: 10.969 ops/ms
Iteration   2: 10.993 ops/ms
Iteration   3: 11.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.017 ±(99.9%) 1.164 ops/ms [Average]
  (min, avg, max) = (10.969, 11.017, 11.089), stdev = 0.064
  CI (99.9%): [9.853, 12.181] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.292 ops/ms
# Warmup Iteration   2: 10.093 ops/ms
# Warmup Iteration   3: 10.592 ops/ms
Iteration   1: 10.542 ops/ms
Iteration   2: 10.572 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.576 ±(99.9%) 0.668 ops/ms [Average]
  (min, avg, max) = (10.542, 10.576, 10.615), stdev = 0.037
  CI (99.9%): [9.908, 11.244] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.976 ops/ms
# Warmup Iteration   2: 7.564 ops/ms
# Warmup Iteration   3: 7.851 ops/ms
Iteration   1: 7.827 ops/ms
Iteration   2: 8.018 ops/ms
Iteration   3: 7.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.936 ±(99.9%) 1.799 ops/ms [Average]
  (min, avg, max) = (7.827, 7.936, 8.018), stdev = 0.099
  CI (99.9%): [6.137, 9.735] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.618 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.004 ms/op
Iteration   1: 3.087 ±(99.9%) 0.002 ms/op
Iteration   2: 3.066 ±(99.9%) 0.002 ms/op
Iteration   3: 3.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.066 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (3.044, 3.066, 3.087), stdev = 0.021
  CI (99.9%): [2.675, 3.457] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.805 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.806 ±(99.9%) 0.003 ms/op
Iteration   1: 2.881 ±(99.9%) 0.003 ms/op
Iteration   2: 2.924 ±(99.9%) 0.002 ms/op
Iteration   3: 2.895 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.900 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (2.881, 2.900, 2.924), stdev = 0.022
  CI (99.9%): [2.496, 3.304] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.305 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.002 ms/op
Iteration   1: 3.095 ±(99.9%) 0.003 ms/op
Iteration   2: 3.060 ±(99.9%) 0.001 ms/op
Iteration   3: 3.059 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.072 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.059, 3.072, 3.095), stdev = 0.021
  CI (99.9%): [2.697, 3.446] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.022 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.020 ms/op
Iteration   1: 4.026 ±(99.9%) 0.038 ms/op
Iteration   2: 4.072 ±(99.9%) 0.014 ms/op
Iteration   3: 4.013 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.037 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (4.013, 4.037, 4.072), stdev = 0.031
  CI (99.9%): [3.468, 4.606] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.143 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  9.019 ms/op
                 createUser·p0.9999: 17.159 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.632 ms/op
                 createUser·p0.9999: 16.909 ms/op
                 createUser·p1.00:   18.219 ms/op

Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.182 ms/op
                 createUser·p0.999:  7.481 ms/op
                 createUser·p0.9999: 20.202 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313113
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21520 
    [ 2.500,  5.000) = 290219 
    [ 5.000,  7.500) = 979 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.600 ms/op
     p(99.9900) =     19.749 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.956 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
Iteration   1: 2.908 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.282 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.160 ms/op
                 existUser·p0.9999: 17.563 ms/op
                 existUser·p1.00:   18.973 ms/op

Iteration   2: 2.911 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  6.308 ms/op
                 existUser·p0.9999: 14.566 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   3: 2.853 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.709 ms/op
                 existUser·p0.9999: 15.315 ms/op
                 existUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332133
  mean =      2.890 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1930 
    [ 1.250,  2.500) = 46088 
    [ 2.500,  3.750) = 273092 
    [ 3.750,  5.000) = 10257 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 201 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.413 ms/op
     p(99.9900) =     15.499 ms/op
     p(99.9990) =     17.838 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.083 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
Iteration   1: 3.077 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  6.523 ms/op
                 getUser·p0.9999: 13.619 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.544 ms/op
                 getUser·p0.999:  8.374 ms/op
                 getUser·p0.9999: 16.843 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  6.172 ms/op
                 getUser·p0.9999: 30.769 ms/op
                 getUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313097
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16189 
    [ 2.500,  5.000) = 295355 
    [ 5.000,  7.500) = 1301 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.094 ms/op
     p(99.9900) =     30.278 ms/op
     p(99.9990) =     30.966 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


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
# Warmup Iteration   1: 5.482 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.010 ms/op
Iteration   1: 4.044 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 24.281 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   2: 4.012 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.904 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 22.054 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   3: 4.051 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.181 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.006 ms/op
                 listUser·p0.999:  16.629 ms/op
                 listUser·p0.9999: 18.615 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238039
  mean =      4.036 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3056 
    [ 2.500,  5.000) = 209984 
    [ 5.000,  7.500) = 23632 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.034 ms/op
     p(99.9000) =     16.416 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     24.571 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.121 ± 0.959  ops/ms
ClientGrpc.existUser                       thrpt       3  11.017 ± 1.164  ops/ms
ClientGrpc.getUser                         thrpt       3  10.576 ± 0.668  ops/ms
ClientGrpc.listUser                        thrpt       3   7.936 ± 1.799  ops/ms
ClientGrpc.createUser                       avgt       3   3.066 ± 0.391   ms/op
ClientGrpc.existUser                        avgt       3   2.900 ± 0.404   ms/op
ClientGrpc.getUser                          avgt       3   3.072 ± 0.375   ms/op
ClientGrpc.listUser                         avgt       3   4.037 ± 0.569   ms/op
ClientGrpc.createUser                     sample  313113   3.067 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.700           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.600           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.749           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.496           ms/op
ClientGrpc.existUser                      sample  332133   2.890 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.282           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.413           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.499           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.973           ms/op
ClientGrpc.getUser                        sample  313097   3.067 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.684           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.094           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.278           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.064           ms/op
ClientGrpc.listUser                       sample  238039   4.036 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.827           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.034           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.416           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.429           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.642           ms/op
