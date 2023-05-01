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
# Warmup Iteration   1: 2.324 ops/ms
# Warmup Iteration   2: 5.094 ops/ms
# Warmup Iteration   3: 7.291 ops/ms
Iteration   1: 7.480 ops/ms
Iteration   2: 7.642 ops/ms
Iteration   3: 7.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.676 ±(99.9%) 3.924 ops/ms [Average]
  (min, avg, max) = (7.480, 7.676, 7.906), stdev = 0.215
  CI (99.9%): [3.752, 11.600] (assumes normal distribution)


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
# Warmup Iteration   1: 5.275 ops/ms
# Warmup Iteration   2: 7.834 ops/ms
# Warmup Iteration   3: 7.709 ops/ms
Iteration   1: 7.991 ops/ms
Iteration   2: 7.744 ops/ms
Iteration   3: 7.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.786 ±(99.9%) 3.425 ops/ms [Average]
  (min, avg, max) = (7.623, 7.786, 7.991), stdev = 0.188
  CI (99.9%): [4.361, 11.211] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.418 ops/ms
# Warmup Iteration   2: 7.147 ops/ms
# Warmup Iteration   3: 7.481 ops/ms
Iteration   1: 7.319 ops/ms
Iteration   2: 7.577 ops/ms
Iteration   3: 7.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.446 ±(99.9%) 2.355 ops/ms [Average]
  (min, avg, max) = (7.319, 7.446, 7.577), stdev = 0.129
  CI (99.9%): [5.092, 9.801] (assumes normal distribution)


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
# Warmup Iteration   1: 3.637 ops/ms
# Warmup Iteration   2: 5.289 ops/ms
# Warmup Iteration   3: 5.747 ops/ms
Iteration   1: 5.596 ops/ms
Iteration   2: 5.616 ops/ms
Iteration   3: 5.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.652 ±(99.9%) 1.462 ops/ms [Average]
  (min, avg, max) = (5.596, 5.652, 5.744), stdev = 0.080
  CI (99.9%): [4.190, 7.114] (assumes normal distribution)


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
# Warmup Iteration   1: 6.346 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.294 ±(99.9%) 0.007 ms/op
Iteration   1: 4.265 ±(99.9%) 0.004 ms/op
Iteration   2: 4.207 ±(99.9%) 0.003 ms/op
Iteration   3: 4.181 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.217 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (4.181, 4.217, 4.265), stdev = 0.043
  CI (99.9%): [3.435, 5.000] (assumes normal distribution)


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
# Warmup Iteration   1: 5.510 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.003 ms/op
Iteration   1: 4.031 ±(99.9%) 0.003 ms/op
Iteration   2: 3.918 ±(99.9%) 0.003 ms/op
Iteration   3: 3.844 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.931 ±(99.9%) 1.716 ms/op [Average]
  (min, avg, max) = (3.844, 3.931, 4.031), stdev = 0.094
  CI (99.9%): [2.215, 5.647] (assumes normal distribution)


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
# Warmup Iteration   1: 6.629 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.369 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.130 ±(99.9%) 0.008 ms/op
Iteration   1: 4.190 ±(99.9%) 0.004 ms/op
Iteration   2: 4.242 ±(99.9%) 0.004 ms/op
Iteration   3: 4.060 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.164 ±(99.9%) 1.707 ms/op [Average]
  (min, avg, max) = (4.060, 4.164, 4.242), stdev = 0.094
  CI (99.9%): [2.458, 5.871] (assumes normal distribution)


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
# Warmup Iteration   1: 8.199 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 5.958 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.693 ±(99.9%) 0.028 ms/op
Iteration   1: 5.501 ±(99.9%) 0.019 ms/op
Iteration   2: 5.513 ±(99.9%) 0.016 ms/op
Iteration   3: 5.467 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.494 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (5.467, 5.494, 5.513), stdev = 0.024
  CI (99.9%): [5.060, 5.928] (assumes normal distribution)


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
# Warmup Iteration   1: 6.313 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.362 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.014 ms/op
Iteration   1: 3.984 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  11.076 ms/op
                 createUser·p0.9999: 15.040 ms/op
                 createUser·p1.00:   15.450 ms/op

Iteration   2: 4.055 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   5.054 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   7.045 ms/op
                 createUser·p0.999:  14.320 ms/op
                 createUser·p0.9999: 20.264 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 4.137 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   5.259 ms/op
                 createUser·p0.95:   5.767 ms/op
                 createUser·p0.99:   7.971 ms/op
                 createUser·p0.999:  14.172 ms/op
                 createUser·p0.9999: 27.656 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 236677
  mean =      4.057 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7618 
    [ 2.500,  5.000) = 200405 
    [ 5.000,  7.500) = 26359 
    [ 7.500, 10.000) = 1742 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     12.675 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     27.689 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 6.073 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.544 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.012 ms/op
Iteration   1: 3.940 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   3.815 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   7.635 ms/op
                 existUser·p0.999:  12.150 ms/op
                 existUser·p0.9999: 15.678 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   2: 3.925 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   7.266 ms/op
                 existUser·p0.999:  11.141 ms/op
                 existUser·p0.9999: 18.973 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   3: 3.907 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   7.406 ms/op
                 existUser·p0.999:  13.595 ms/op
                 existUser·p0.9999: 35.574 ms/op
                 existUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 244432
  mean =      3.924 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9202 
    [ 2.500,  5.000) = 212463 
    [ 5.000,  7.500) = 20419 
    [ 7.500, 10.000) = 1864 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     11.740 ms/op
     p(99.9900) =     32.622 ms/op
     p(99.9990) =     35.754 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 6.110 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.460 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.014 ms/op
Iteration   1: 4.186 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   4.051 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   5.972 ms/op
                 getUser·p0.99:   8.217 ms/op
                 getUser·p0.999:  12.009 ms/op
                 getUser·p0.9999: 15.648 ms/op
                 getUser·p1.00:   15.991 ms/op

Iteration   2: 4.138 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.792 ms/op
                 getUser·p0.99:   8.176 ms/op
                 getUser·p0.999:  12.517 ms/op
                 getUser·p0.9999: 33.429 ms/op
                 getUser·p1.00:   35.127 ms/op

Iteration   3: 4.163 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   8.375 ms/op
                 getUser·p0.999:  13.947 ms/op
                 getUser·p0.9999: 22.096 ms/op
                 getUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 230567
  mean =      4.162 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8796 
    [ 2.500,  5.000) = 187351 
    [ 5.000,  7.500) = 30979 
    [ 7.500, 10.000) = 2691 
    [10.000, 12.500) = 477 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      8.266 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     28.504 ms/op
     p(99.9990) =     35.042 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 8.206 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.733 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.342 ±(99.9%) 0.022 ms/op
Iteration   1: 5.390 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.628 ms/op
                 listUser·p0.50:   5.079 ms/op
                 listUser·p0.90:   7.094 ms/op
                 listUser·p0.95:   8.083 ms/op
                 listUser·p0.99:   10.875 ms/op
                 listUser·p0.999:  19.683 ms/op
                 listUser·p0.9999: 24.936 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 5.541 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   7.389 ms/op
                 listUser·p0.95:   8.323 ms/op
                 listUser·p0.99:   10.693 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 19.341 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 5.474 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   7.365 ms/op
                 listUser·p0.95:   8.331 ms/op
                 listUser·p0.99:   10.748 ms/op
                 listUser·p0.999:  28.246 ms/op
                 listUser·p0.9999: 30.276 ms/op
                 listUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175376
  mean =      5.468 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 268 
    [ 2.500,  5.000) = 76569 
    [ 5.000,  7.500) = 83432 
    [ 7.500, 10.000) = 12259 
    [10.000, 12.500) = 2089 
    [12.500, 15.000) = 349 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      7.291 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     21.229 ms/op
     p(99.9900) =     29.343 ms/op
     p(99.9990) =     31.202 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.676 ± 3.924  ops/ms
ClientGrpc.existUser                       thrpt       3   7.786 ± 3.425  ops/ms
ClientGrpc.getUser                         thrpt       3   7.446 ± 2.355  ops/ms
ClientGrpc.listUser                        thrpt       3   5.652 ± 1.462  ops/ms
ClientGrpc.createUser                       avgt       3   4.217 ± 0.782   ms/op
ClientGrpc.existUser                        avgt       3   3.931 ± 1.716   ms/op
ClientGrpc.getUser                          avgt       3   4.164 ± 1.707   ms/op
ClientGrpc.listUser                         avgt       3   5.494 ± 0.434   ms/op
ClientGrpc.createUser                     sample  236677   4.057 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.776           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.136           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.652           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.447           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.675           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.394           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.689           ms/op
ClientGrpc.existUser                      sample  244432   3.924 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.812           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.956           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.472           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.447           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.740           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.622           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.848           ms/op
ClientGrpc.getUser                        sample  230567   4.162 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.761           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.018           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.898           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.266           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.927           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.504           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.127           ms/op
ClientGrpc.listUser                       sample  175376   5.468 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.214           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.249           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.764           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.229           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.343           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.523           ms/op
