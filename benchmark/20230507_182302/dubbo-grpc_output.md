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
# Warmup Iteration   1: 2.077 ops/ms
# Warmup Iteration   2: 5.062 ops/ms
# Warmup Iteration   3: 6.107 ops/ms
Iteration   1: 7.040 ops/ms
Iteration   2: 6.993 ops/ms
Iteration   3: 6.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.980 ±(99.9%) 1.229 ops/ms [Average]
  (min, avg, max) = (6.907, 6.980, 7.040), stdev = 0.067
  CI (99.9%): [5.752, 8.209] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.427 ops/ms
# Warmup Iteration   2: 7.239 ops/ms
# Warmup Iteration   3: 7.998 ops/ms
Iteration   1: 7.893 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 8.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.104 ±(99.9%) 3.514 ops/ms [Average]
  (min, avg, max) = (7.893, 8.104, 8.269), stdev = 0.193
  CI (99.9%): [4.590, 11.618] (assumes normal distribution)


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
# Warmup Iteration   1: 4.713 ops/ms
# Warmup Iteration   2: 6.730 ops/ms
# Warmup Iteration   3: 7.401 ops/ms
Iteration   1: 7.445 ops/ms
Iteration   2: 7.553 ops/ms
Iteration   3: 7.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.462 ±(99.9%) 1.536 ops/ms [Average]
  (min, avg, max) = (7.387, 7.462, 7.553), stdev = 0.084
  CI (99.9%): [5.925, 8.998] (assumes normal distribution)


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
# Warmup Iteration   1: 3.470 ops/ms
# Warmup Iteration   2: 5.555 ops/ms
# Warmup Iteration   3: 5.806 ops/ms
Iteration   1: 5.766 ops/ms
Iteration   2: 5.791 ops/ms
Iteration   3: 5.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.847 ±(99.9%) 2.156 ops/ms [Average]
  (min, avg, max) = (5.766, 5.847, 5.982), stdev = 0.118
  CI (99.9%): [3.691, 8.002] (assumes normal distribution)


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
# Warmup Iteration   1: 7.149 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.842 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.638 ±(99.9%) 0.005 ms/op
Iteration   1: 4.337 ±(99.9%) 0.005 ms/op
Iteration   2: 4.298 ±(99.9%) 0.003 ms/op
Iteration   3: 4.228 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.288 ±(99.9%) 1.014 ms/op [Average]
  (min, avg, max) = (4.228, 4.288, 4.337), stdev = 0.056
  CI (99.9%): [3.273, 5.302] (assumes normal distribution)


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
# Warmup Iteration   1: 6.036 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.312 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.004 ms/op
Iteration   1: 4.061 ±(99.9%) 0.003 ms/op
Iteration   2: 3.802 ±(99.9%) 0.003 ms/op
Iteration   3: 3.867 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.910 ±(99.9%) 2.457 ms/op [Average]
  (min, avg, max) = (3.802, 3.910, 4.061), stdev = 0.135
  CI (99.9%): [1.453, 6.367] (assumes normal distribution)


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
# Warmup Iteration   1: 6.626 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.543 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.009 ms/op
Iteration   1: 4.252 ±(99.9%) 0.003 ms/op
Iteration   2: 4.079 ±(99.9%) 0.005 ms/op
Iteration   3: 4.209 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.180 ±(99.9%) 1.647 ms/op [Average]
  (min, avg, max) = (4.079, 4.180, 4.252), stdev = 0.090
  CI (99.9%): [2.533, 5.828] (assumes normal distribution)


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
# Warmup Iteration   1: 8.748 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 6.083 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.784 ±(99.9%) 0.015 ms/op
Iteration   1: 5.733 ±(99.9%) 0.030 ms/op
Iteration   2: 5.437 ±(99.9%) 0.014 ms/op
Iteration   3: 5.327 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.499 ±(99.9%) 3.836 ms/op [Average]
  (min, avg, max) = (5.327, 5.499, 5.733), stdev = 0.210
  CI (99.9%): [1.663, 9.335] (assumes normal distribution)


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
# Warmup Iteration   1: 6.938 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.651 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.014 ms/op
Iteration   1: 4.242 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   4.104 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.956 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  12.028 ms/op
                 createUser·p0.9999: 19.151 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   2: 4.202 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.169 ms/op
                 createUser·p0.95:   5.554 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  9.906 ms/op
                 createUser·p0.9999: 18.060 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   3: 4.167 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   4.059 ms/op
                 createUser·p0.90:   5.186 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   7.528 ms/op
                 createUser·p0.999:  12.616 ms/op
                 createUser·p0.9999: 20.020 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 228329
  mean =      4.204 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5214 
    [ 2.500,  5.000) = 189626 
    [ 5.000,  7.500) = 31153 
    [ 7.500, 10.000) = 1726 
    [10.000, 12.500) = 447 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     11.829 ms/op
     p(99.9900) =     18.913 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 6.462 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.312 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.010 ms/op
Iteration   1: 4.129 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.915 ms/op
                 existUser·p0.99:   8.461 ms/op
                 existUser·p0.999:  13.631 ms/op
                 existUser·p0.9999: 17.408 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   2: 4.223 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   4.006 ms/op
                 existUser·p0.90:   5.530 ms/op
                 existUser·p0.95:   6.250 ms/op
                 existUser·p0.99:   8.733 ms/op
                 existUser·p0.999:  13.947 ms/op
                 existUser·p0.9999: 18.575 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 4.547 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   4.252 ms/op
                 existUser·p0.90:   6.238 ms/op
                 existUser·p0.95:   7.258 ms/op
                 existUser·p0.99:   9.798 ms/op
                 existUser·p0.999:  14.270 ms/op
                 existUser·p0.9999: 21.885 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 223708
  mean =      4.292 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6286 
    [ 2.500,  5.000) = 175102 
    [ 5.000,  7.500) = 36405 
    [ 7.500, 10.000) = 4594 
    [10.000, 12.500) = 913 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      5.661 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      9.142 ms/op
     p(99.9000) =     13.948 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     22.463 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 7.170 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.839 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.371 ±(99.9%) 0.013 ms/op
Iteration   1: 4.321 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   4.182 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   6.029 ms/op
                 getUser·p0.99:   8.086 ms/op
                 getUser·p0.999:  12.363 ms/op
                 getUser·p0.9999: 16.783 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 4.467 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.710 ms/op
                 getUser·p0.95:   6.275 ms/op
                 getUser·p0.99:   7.913 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 18.514 ms/op
                 getUser·p1.00:   18.612 ms/op

Iteration   3: 4.466 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.726 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   8.192 ms/op
                 getUser·p0.999:  13.484 ms/op
                 getUser·p0.9999: 21.677 ms/op
                 getUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217259
  mean =      4.417 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4520 
    [ 2.500,  5.000) = 163344 
    [ 5.000,  7.500) = 46295 
    [ 7.500, 10.000) = 2351 
    [10.000, 12.500) = 544 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.193 ms/op
     p(99.0000) =      8.077 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     18.556 ms/op
     p(99.9990) =     22.167 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 8.628 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 5.869 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.288 ±(99.9%) 0.019 ms/op
Iteration   1: 5.339 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   7.045 ms/op
                 listUser·p0.95:   8.110 ms/op
                 listUser·p0.99:   10.338 ms/op
                 listUser·p0.999:  16.649 ms/op
                 listUser·p0.9999: 19.236 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 5.607 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   7.602 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   11.141 ms/op
                 listUser·p0.999:  18.084 ms/op
                 listUser·p0.9999: 20.714 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 5.431 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.655 ms/op
                 listUser·p0.99:   11.649 ms/op
                 listUser·p0.999:  23.567 ms/op
                 listUser·p0.9999: 32.477 ms/op
                 listUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175926
  mean =      5.457 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 346 
    [ 2.500,  5.000) = 81506 
    [ 5.000,  7.500) = 77101 
    [ 7.500, 10.000) = 13705 
    [10.000, 12.500) = 2375 
    [12.500, 15.000) = 503 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      7.447 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     31.602 ms/op
     p(99.9990) =     32.693 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.980 ± 1.229  ops/ms
ClientGrpc.existUser                       thrpt       3   8.104 ± 3.514  ops/ms
ClientGrpc.getUser                         thrpt       3   7.462 ± 1.536  ops/ms
ClientGrpc.listUser                        thrpt       3   5.847 ± 2.156  ops/ms
ClientGrpc.createUser                       avgt       3   4.288 ± 1.014   ms/op
ClientGrpc.existUser                        avgt       3   3.910 ± 2.457   ms/op
ClientGrpc.getUser                          avgt       3   4.180 ± 1.647   ms/op
ClientGrpc.listUser                         avgt       3   5.499 ± 3.836   ms/op
ClientGrpc.createUser                     sample  228329   4.204 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.871           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.259           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.726           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.545           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.829           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.913           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.775           ms/op
ClientGrpc.existUser                      sample  223708   4.292 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.603           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.051           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.661           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.537           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.142           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.948           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.382           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.577           ms/op
ClientGrpc.getUser                        sample  217259   4.417 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.936           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.193           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.077           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.304           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.556           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.282           ms/op
ClientGrpc.listUser                       sample  175926   5.457 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.051           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.447           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.059           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.121           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.602           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.768           ms/op
