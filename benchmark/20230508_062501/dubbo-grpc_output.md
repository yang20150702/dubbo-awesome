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
# Warmup Iteration   1: 1.895 ops/ms
# Warmup Iteration   2: 4.675 ops/ms
# Warmup Iteration   3: 6.704 ops/ms
Iteration   1: 6.780 ops/ms
Iteration   2: 6.854 ops/ms
Iteration   3: 6.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.869 ±(99.9%) 1.788 ops/ms [Average]
  (min, avg, max) = (6.780, 6.869, 6.974), stdev = 0.098
  CI (99.9%): [5.081, 8.658] (assumes normal distribution)


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
# Warmup Iteration   1: 4.402 ops/ms
# Warmup Iteration   2: 6.843 ops/ms
# Warmup Iteration   3: 7.333 ops/ms
Iteration   1: 7.454 ops/ms
Iteration   2: 7.635 ops/ms
Iteration   3: 7.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.573 ±(99.9%) 1.876 ops/ms [Average]
  (min, avg, max) = (7.454, 7.573, 7.635), stdev = 0.103
  CI (99.9%): [5.697, 9.448] (assumes normal distribution)


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
# Warmup Iteration   1: 3.842 ops/ms
# Warmup Iteration   2: 6.390 ops/ms
# Warmup Iteration   3: 6.990 ops/ms
Iteration   1: 6.861 ops/ms
Iteration   2: 6.909 ops/ms
Iteration   3: 6.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.886 ±(99.9%) 0.435 ops/ms [Average]
  (min, avg, max) = (6.861, 6.886, 6.909), stdev = 0.024
  CI (99.9%): [6.451, 7.321] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.248 ops/ms
# Warmup Iteration   2: 4.805 ops/ms
# Warmup Iteration   3: 5.523 ops/ms
Iteration   1: 5.605 ops/ms
Iteration   2: 5.433 ops/ms
Iteration   3: 5.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.533 ±(99.9%) 1.624 ops/ms [Average]
  (min, avg, max) = (5.433, 5.533, 5.605), stdev = 0.089
  CI (99.9%): [3.909, 7.156] (assumes normal distribution)


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
# Warmup Iteration   1: 7.153 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.866 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.551 ±(99.9%) 0.005 ms/op
Iteration   1: 4.584 ±(99.9%) 0.004 ms/op
Iteration   2: 4.370 ±(99.9%) 0.003 ms/op
Iteration   3: 4.378 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.444 ±(99.9%) 2.208 ms/op [Average]
  (min, avg, max) = (4.370, 4.444, 4.584), stdev = 0.121
  CI (99.9%): [2.236, 6.652] (assumes normal distribution)


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
# Warmup Iteration   1: 6.350 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.590 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.240 ±(99.9%) 0.016 ms/op
Iteration   1: 4.397 ±(99.9%) 0.005 ms/op
Iteration   2: 4.142 ±(99.9%) 0.005 ms/op
Iteration   3: 4.152 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.230 ±(99.9%) 2.634 ms/op [Average]
  (min, avg, max) = (4.142, 4.230, 4.397), stdev = 0.144
  CI (99.9%): [1.596, 6.864] (assumes normal distribution)


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
# Warmup Iteration   1: 7.221 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.790 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.713 ±(99.9%) 0.019 ms/op
Iteration   1: 4.369 ±(99.9%) 0.005 ms/op
Iteration   2: 4.430 ±(99.9%) 0.004 ms/op
Iteration   3: 4.400 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.400 ±(99.9%) 0.564 ms/op [Average]
  (min, avg, max) = (4.369, 4.400, 4.430), stdev = 0.031
  CI (99.9%): [3.836, 4.963] (assumes normal distribution)


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
# Warmup Iteration   1: 9.342 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 6.892 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.450 ±(99.9%) 0.027 ms/op
Iteration   1: 6.133 ±(99.9%) 0.020 ms/op
Iteration   2: 5.827 ±(99.9%) 0.016 ms/op
Iteration   3: 5.881 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.947 ±(99.9%) 2.986 ms/op [Average]
  (min, avg, max) = (5.827, 5.947, 6.133), stdev = 0.164
  CI (99.9%): [2.962, 8.933] (assumes normal distribution)


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
# Warmup Iteration   1: 7.179 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.880 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.436 ±(99.9%) 0.016 ms/op
Iteration   1: 4.304 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   4.186 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.923 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  10.808 ms/op
                 createUser·p0.9999: 15.380 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   2: 4.442 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   4.293 ms/op
                 createUser·p0.90:   5.620 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   8.128 ms/op
                 createUser·p0.999:  11.660 ms/op
                 createUser·p0.9999: 18.271 ms/op
                 createUser·p1.00:   18.678 ms/op

Iteration   3: 4.260 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   4.153 ms/op
                 createUser·p0.90:   5.308 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   7.897 ms/op
                 createUser·p0.999:  12.448 ms/op
                 createUser·p0.9999: 22.379 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 221654
  mean =      4.334 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5104 
    [ 2.500,  5.000) = 174462 
    [ 5.000,  7.500) = 39328 
    [ 7.500, 10.000) = 2181 
    [10.000, 12.500) = 415 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     21.190 ms/op
     p(99.9990) =     22.811 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 6.322 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.676 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.394 ±(99.9%) 0.013 ms/op
Iteration   1: 4.406 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.685 ms/op
                 existUser·p0.95:   6.455 ms/op
                 existUser·p0.99:   9.585 ms/op
                 existUser·p0.999:  14.194 ms/op
                 existUser·p0.9999: 22.429 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   2: 4.456 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   4.317 ms/op
                 existUser·p0.90:   5.579 ms/op
                 existUser·p0.95:   6.070 ms/op
                 existUser·p0.99:   7.684 ms/op
                 existUser·p0.999:  11.808 ms/op
                 existUser·p0.9999: 20.129 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   3: 4.346 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.513 ms/op
                 existUser·p0.95:   6.144 ms/op
                 existUser·p0.99:   8.739 ms/op
                 existUser·p0.999:  13.201 ms/op
                 existUser·p0.9999: 20.173 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 218072
  mean =      4.402 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6286 
    [ 2.500,  5.000) = 166481 
    [ 5.000,  7.500) = 40999 
    [ 7.500, 10.000) = 3062 
    [10.000, 12.500) = 890 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.587 ms/op
     p(95.0000) =      6.210 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     13.450 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     22.902 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 7.007 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.883 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.815 ±(99.9%) 0.016 ms/op
Iteration   1: 4.626 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   4.489 ms/op
                 getUser·p0.90:   5.841 ms/op
                 getUser·p0.95:   6.423 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  12.956 ms/op
                 getUser·p0.9999: 16.518 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   2: 4.595 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   4.440 ms/op
                 getUser·p0.90:   5.743 ms/op
                 getUser·p0.95:   6.390 ms/op
                 getUser·p0.99:   8.929 ms/op
                 getUser·p0.999:  18.753 ms/op
                 getUser·p0.9999: 32.082 ms/op
                 getUser·p1.00:   32.375 ms/op

Iteration   3: 4.463 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   5.988 ms/op
                 getUser·p0.99:   7.733 ms/op
                 getUser·p0.999:  11.175 ms/op
                 getUser·p0.9999: 26.870 ms/op
                 getUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 210582
  mean =      4.560 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4295 
    [ 2.500,  5.000) = 155198 
    [ 5.000,  7.500) = 47326 
    [ 7.500, 10.000) = 2973 
    [10.000, 12.500) = 446 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.275 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     14.488 ms/op
     p(99.9900) =     28.566 ms/op
     p(99.9990) =     32.276 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 8.742 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 6.212 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.951 ±(99.9%) 0.024 ms/op
Iteration   1: 5.637 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.034 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   11.010 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 20.523 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   2: 5.692 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.741 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   11.092 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 20.407 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   3: 5.717 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  21.666 ms/op
                 listUser·p0.9999: 24.412 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168867
  mean =      5.682 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 179 
    [ 2.500,  5.000) = 60410 
    [ 5.000,  7.500) = 90324 
    [ 7.500, 10.000) = 14559 
    [10.000, 12.500) = 2520 
    [12.500, 15.000) = 476 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.594 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     23.804 ms/op
     p(99.9990) =     24.619 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.869 ± 1.788  ops/ms
ClientGrpc.existUser                       thrpt       3   7.573 ± 1.876  ops/ms
ClientGrpc.getUser                         thrpt       3   6.886 ± 0.435  ops/ms
ClientGrpc.listUser                        thrpt       3   5.533 ± 1.624  ops/ms
ClientGrpc.createUser                       avgt       3   4.444 ± 2.208   ms/op
ClientGrpc.existUser                        avgt       3   4.230 ± 2.634   ms/op
ClientGrpc.getUser                          avgt       3   4.400 ± 0.564   ms/op
ClientGrpc.listUser                         avgt       3   5.947 ± 2.986   ms/op
ClientGrpc.createUser                     sample  221654   4.334 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.906           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.456           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.972           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.897           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.878           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.190           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.938           ms/op
ClientGrpc.existUser                      sample  218072   4.402 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.785           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.587           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.210           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.716           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.450           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.218           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.036           ms/op
ClientGrpc.getUser                        sample  210582   4.560 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.924           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.685           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.275           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.438           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.488           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.566           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.375           ms/op
ClientGrpc.listUser                       sample  168867   5.682 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.128           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.594           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.651           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.190           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.957           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.804           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.642           ms/op
