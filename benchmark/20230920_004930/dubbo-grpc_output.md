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
# Warmup Iteration   1: 3.014 ops/ms
# Warmup Iteration   2: 5.762 ops/ms
# Warmup Iteration   3: 6.796 ops/ms
Iteration   1: 6.863 ops/ms
Iteration   2: 6.826 ops/ms
Iteration   3: 7.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.955 ±(99.9%) 3.511 ops/ms [Average]
  (min, avg, max) = (6.826, 6.955, 7.176), stdev = 0.192
  CI (99.9%): [3.444, 10.466] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.501 ops/ms
# Warmup Iteration   2: 7.674 ops/ms
# Warmup Iteration   3: 8.141 ops/ms
Iteration   1: 8.359 ops/ms
Iteration   2: 8.377 ops/ms
Iteration   3: 8.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.252 ±(99.9%) 3.674 ops/ms [Average]
  (min, avg, max) = (8.019, 8.252, 8.377), stdev = 0.201
  CI (99.9%): [4.578, 11.925] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.972 ops/ms
# Warmup Iteration   2: 7.263 ops/ms
# Warmup Iteration   3: 7.471 ops/ms
Iteration   1: 8.011 ops/ms
Iteration   2: 7.880 ops/ms
Iteration   3: 7.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.913 ±(99.9%) 1.584 ops/ms [Average]
  (min, avg, max) = (7.847, 7.913, 8.011), stdev = 0.087
  CI (99.9%): [6.329, 9.496] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 4.488 ops/ms
# Warmup Iteration   2: 6.090 ops/ms
# Warmup Iteration   3: 6.362 ops/ms
Iteration   1: 6.478 ops/ms
Iteration   2: 6.310 ops/ms
Iteration   3: 6.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.433 ±(99.9%) 1.964 ops/ms [Average]
  (min, avg, max) = (6.310, 6.433, 6.511), stdev = 0.108
  CI (99.9%): [4.469, 8.396] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.759 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.024 ms/op
Iteration   1: 4.099 ±(99.9%) 0.004 ms/op
Iteration   2: 4.037 ±(99.9%) 0.003 ms/op
Iteration   3: 4.087 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.074 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (4.037, 4.074, 4.099), stdev = 0.033
  CI (99.9%): [3.476, 4.673] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.320 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.002 ms/op
Iteration   1: 3.807 ±(99.9%) 0.004 ms/op
Iteration   2: 3.821 ±(99.9%) 0.003 ms/op
Iteration   3: 3.779 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.802 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.779, 3.802, 3.821), stdev = 0.021
  CI (99.9%): [3.414, 4.190] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.244 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.355 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.005 ms/op
Iteration   1: 4.073 ±(99.9%) 0.045 ms/op
Iteration   2: 4.102 ±(99.9%) 0.003 ms/op
Iteration   3: 4.108 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.094 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (4.073, 4.094, 4.108), stdev = 0.019
  CI (99.9%): [3.757, 4.432] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 6.454 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.614 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.991 ±(99.9%) 0.010 ms/op
Iteration   1: 5.113 ±(99.9%) 0.012 ms/op
Iteration   2: 5.210 ±(99.9%) 0.012 ms/op
Iteration   3: 5.137 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.153 ±(99.9%) 0.920 ms/op [Average]
  (min, avg, max) = (5.113, 5.153, 5.210), stdev = 0.050
  CI (99.9%): [4.233, 6.073] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.516 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.254 ±(99.9%) 0.012 ms/op
Iteration   1: 4.177 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  13.566 ms/op
                 createUser·p0.9999: 16.150 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   2: 4.219 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   4.059 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  15.120 ms/op
                 createUser·p0.9999: 19.694 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   3: 4.167 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.956 ms/op
                 createUser·p0.99:   8.302 ms/op
                 createUser·p0.999:  15.375 ms/op
                 createUser·p0.9999: 30.157 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 229200
  mean =      4.188 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9088 
    [ 2.500,  5.000) = 185639 
    [ 5.000,  7.500) = 30900 
    [ 7.500, 10.000) = 2400 
    [10.000, 12.500) = 833 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      8.290 ms/op
     p(99.9000) =     14.002 ms/op
     p(99.9900) =     29.688 ms/op
     p(99.9990) =     30.684 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.258 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.012 ms/op
Iteration   1: 4.019 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   8.053 ms/op
                 existUser·p0.999:  12.335 ms/op
                 existUser·p0.9999: 15.796 ms/op
                 existUser·p1.00:   16.400 ms/op

Iteration   2: 3.980 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   7.586 ms/op
                 existUser·p0.999:  11.338 ms/op
                 existUser·p0.9999: 21.168 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   3: 4.102 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   5.235 ms/op
                 existUser·p0.95:   5.947 ms/op
                 existUser·p0.99:   8.567 ms/op
                 existUser·p0.999:  14.957 ms/op
                 existUser·p0.9999: 22.282 ms/op
                 existUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 237905
  mean =      4.033 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7515 
    [ 2.500,  5.000) = 202905 
    [ 5.000,  7.500) = 24286 
    [ 7.500, 10.000) = 2307 
    [10.000, 12.500) = 560 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     24.662 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.771 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.381 ±(99.9%) 0.014 ms/op
Iteration   1: 4.191 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   7.877 ms/op
                 getUser·p0.999:  11.895 ms/op
                 getUser·p0.9999: 16.843 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   2: 4.192 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   4.002 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   8.297 ms/op
                 getUser·p0.999:  14.768 ms/op
                 getUser·p0.9999: 28.325 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   3: 4.280 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   4.125 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   8.331 ms/op
                 getUser·p0.999:  13.986 ms/op
                 getUser·p0.9999: 20.366 ms/op
                 getUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227294
  mean =      4.221 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5827 
    [ 2.500,  5.000) = 186838 
    [ 5.000,  7.500) = 31282 
    [ 7.500, 10.000) = 2478 
    [10.000, 12.500) = 600 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     25.997 ms/op
     p(99.9990) =     29.178 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.920 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.640 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.405 ±(99.9%) 0.021 ms/op
Iteration   1: 5.105 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.782 ms/op
                 listUser·p0.99:   10.027 ms/op
                 listUser·p0.999:  15.799 ms/op
                 listUser·p0.9999: 21.222 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   2: 5.318 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   4.973 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   7.889 ms/op
                 listUser·p0.99:   10.093 ms/op
                 listUser·p0.999:  21.417 ms/op
                 listUser·p0.9999: 24.149 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   3: 5.306 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   7.037 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   10.158 ms/op
                 listUser·p0.999:  21.797 ms/op
                 listUser·p0.9999: 35.057 ms/op
                 listUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 183273
  mean =      5.241 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 283 
    [ 2.500,  5.000) = 100150 
    [ 5.000,  7.500) = 70405 
    [ 7.500, 10.000) = 10482 
    [10.000, 12.500) = 1431 
    [12.500, 15.000) = 211 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      6.988 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     19.545 ms/op
     p(99.9900) =     28.564 ms/op
     p(99.9990) =     35.466 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.955 ± 3.511  ops/ms
ClientGrpc.existUser                       thrpt       3   8.252 ± 3.674  ops/ms
ClientGrpc.getUser                         thrpt       3   7.913 ± 1.584  ops/ms
ClientGrpc.listUser                        thrpt       3   6.433 ± 1.964  ops/ms
ClientGrpc.createUser                       avgt       3   4.074 ± 0.599   ms/op
ClientGrpc.existUser                        avgt       3   3.802 ± 0.388   ms/op
ClientGrpc.getUser                          avgt       3   4.094 ± 0.338   ms/op
ClientGrpc.listUser                         avgt       3   5.153 ± 0.920   ms/op
ClientGrpc.createUser                     sample  229200   4.188 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.990           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.022           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.333           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.980           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.290           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.002           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.688           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.736           ms/op
ClientGrpc.existUser                      sample  237905   4.033 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.827           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.112           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.718           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.020           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.468           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.758           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.707           ms/op
ClientGrpc.getUser                        sample  227294   4.221 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.031           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.051           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.333           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.923           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.167           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.042           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.997           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.262           ms/op
ClientGrpc.listUser                       sample  183273   5.241 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.126           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.873           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.093           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.545           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.564           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.521           ms/op
