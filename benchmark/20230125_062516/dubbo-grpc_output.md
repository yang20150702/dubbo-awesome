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
# Warmup Iteration   1: 2.584 ops/ms
# Warmup Iteration   2: 6.053 ops/ms
# Warmup Iteration   3: 7.394 ops/ms
Iteration   1: 7.292 ops/ms
Iteration   2: 7.315 ops/ms
Iteration   3: 7.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.284 ±(99.9%) 0.649 ops/ms [Average]
  (min, avg, max) = (7.245, 7.284, 7.315), stdev = 0.036
  CI (99.9%): [6.634, 7.933] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.205 ops/ms
# Warmup Iteration   2: 7.079 ops/ms
# Warmup Iteration   3: 7.551 ops/ms
Iteration   1: 7.498 ops/ms
Iteration   2: 7.367 ops/ms
Iteration   3: 7.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.410 ±(99.9%) 1.395 ops/ms [Average]
  (min, avg, max) = (7.365, 7.410, 7.498), stdev = 0.076
  CI (99.9%): [6.015, 8.805] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.743 ops/ms
# Warmup Iteration   2: 6.619 ops/ms
# Warmup Iteration   3: 6.873 ops/ms
Iteration   1: 7.162 ops/ms
Iteration   2: 7.427 ops/ms
Iteration   3: 7.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.352 ±(99.9%) 3.014 ops/ms [Average]
  (min, avg, max) = (7.162, 7.352, 7.465), stdev = 0.165
  CI (99.9%): [4.338, 10.365] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.463 ops/ms
# Warmup Iteration   2: 4.986 ops/ms
# Warmup Iteration   3: 5.303 ops/ms
Iteration   1: 5.331 ops/ms
Iteration   2: 5.423 ops/ms
Iteration   3: 5.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.413 ±(99.9%) 1.393 ops/ms [Average]
  (min, avg, max) = (5.331, 5.413, 5.483), stdev = 0.076
  CI (99.9%): [4.020, 6.805] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.683 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.762 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 4.494 ±(99.9%) 0.003 ms/op
Iteration   1: 4.483 ±(99.9%) 0.003 ms/op
Iteration   2: 4.457 ±(99.9%) 0.002 ms/op
Iteration   3: 4.418 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.453 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (4.418, 4.453, 4.483), stdev = 0.033
  CI (99.9%): [3.849, 5.057] (assumes normal distribution)


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
# Warmup Iteration   1: 5.534 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.287 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.003 ms/op
Iteration   1: 4.095 ±(99.9%) 0.004 ms/op
Iteration   2: 4.147 ±(99.9%) 0.004 ms/op
Iteration   3: 4.053 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.098 ±(99.9%) 0.862 ms/op [Average]
  (min, avg, max) = (4.053, 4.098, 4.147), stdev = 0.047
  CI (99.9%): [3.236, 4.961] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.126 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.650 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.450 ±(99.9%) 0.003 ms/op
Iteration   1: 4.346 ±(99.9%) 0.004 ms/op
Iteration   2: 4.376 ±(99.9%) 0.004 ms/op
Iteration   3: 4.229 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.317 ±(99.9%) 1.418 ms/op [Average]
  (min, avg, max) = (4.229, 4.317, 4.376), stdev = 0.078
  CI (99.9%): [2.899, 5.735] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.681 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.804 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.563 ±(99.9%) 0.013 ms/op
Iteration   1: 5.439 ±(99.9%) 0.012 ms/op
Iteration   2: 5.529 ±(99.9%) 0.016 ms/op
Iteration   3: 5.352 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.440 ±(99.9%) 1.614 ms/op [Average]
  (min, avg, max) = (5.352, 5.440, 5.529), stdev = 0.088
  CI (99.9%): [3.826, 7.054] (assumes normal distribution)


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
# Warmup Iteration   1: 6.226 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.578 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.357 ±(99.9%) 0.016 ms/op
Iteration   1: 4.385 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.652 ms/op
                 createUser·p0.95:   6.128 ms/op
                 createUser·p0.99:   7.641 ms/op
                 createUser·p0.999:  10.682 ms/op
                 createUser·p0.9999: 15.723 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   2: 4.323 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.489 ms/op
                 createUser·p0.95:   5.956 ms/op
                 createUser·p0.99:   7.610 ms/op
                 createUser·p0.999:  11.142 ms/op
                 createUser·p0.9999: 17.846 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   3: 4.272 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   4.133 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.881 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  12.190 ms/op
                 createUser·p0.9999: 20.676 ms/op
                 createUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222075
  mean =      4.326 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3164 
    [ 2.500,  5.000) = 173001 
    [ 5.000,  7.500) = 43474 
    [ 7.500, 10.000) = 1881 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     11.451 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     21.274 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.633 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.013 ms/op
Iteration   1: 4.107 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.372 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.325 ms/op
                 existUser·p0.95:   5.743 ms/op
                 existUser·p0.99:   7.283 ms/op
                 existUser·p0.999:  11.749 ms/op
                 existUser·p0.9999: 18.180 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   2: 4.014 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   7.381 ms/op
                 existUser·p0.999:  11.726 ms/op
                 existUser·p0.9999: 29.591 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   3: 3.838 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.817 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   7.119 ms/op
                 existUser·p0.999:  11.993 ms/op
                 existUser·p0.9999: 18.973 ms/op
                 existUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 240990
  mean =      3.983 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9063 
    [ 2.500,  5.000) = 204246 
    [ 5.000,  7.500) = 25555 
    [ 7.500, 10.000) = 1654 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     29.753 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.419 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.846 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.503 ±(99.9%) 0.014 ms/op
Iteration   1: 4.487 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.726 ms/op
                 getUser·p0.95:   6.185 ms/op
                 getUser·p0.99:   8.102 ms/op
                 getUser·p0.999:  12.632 ms/op
                 getUser·p0.9999: 15.916 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   2: 4.398 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   5.923 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  13.601 ms/op
                 getUser·p0.9999: 21.266 ms/op
                 getUser·p1.00:   21.430 ms/op

Iteration   3: 4.296 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   7.131 ms/op
                 getUser·p0.999:  11.931 ms/op
                 getUser·p0.9999: 21.678 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218510
  mean =      4.392 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6075 
    [ 2.500,  5.000) = 160676 
    [ 5.000,  7.500) = 49491 
    [ 7.500, 10.000) = 1745 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     21.910 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.309 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.123 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.545 ±(99.9%) 0.020 ms/op
Iteration   1: 5.672 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.780 ms/op
                 listUser·p0.50:   5.341 ms/op
                 listUser·p0.90:   7.602 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   11.274 ms/op
                 listUser·p0.999:  15.306 ms/op
                 listUser·p0.9999: 18.508 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   2: 5.740 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   5.358 ms/op
                 listUser·p0.90:   8.061 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   11.207 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 22.970 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 5.769 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.832 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.780 ms/op
                 listUser·p0.999:  27.583 ms/op
                 listUser·p0.9999: 34.663 ms/op
                 listUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167548
  mean =      5.727 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 283 
    [ 2.500,  5.000) = 62777 
    [ 5.000,  7.500) = 83170 
    [ 7.500, 10.000) = 17508 
    [10.000, 12.500) = 2887 
    [12.500, 15.000) = 559 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.840 ms/op
     p(95.0000) =      8.798 ms/op
     p(99.0000) =     11.420 ms/op
     p(99.9000) =     18.576 ms/op
     p(99.9900) =     32.480 ms/op
     p(99.9990) =     35.659 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.284 ± 0.649  ops/ms
ClientGrpc.existUser                       thrpt       3   7.410 ± 1.395  ops/ms
ClientGrpc.getUser                         thrpt       3   7.352 ± 3.014  ops/ms
ClientGrpc.listUser                        thrpt       3   5.413 ± 1.393  ops/ms
ClientGrpc.createUser                       avgt       3   4.453 ± 0.604   ms/op
ClientGrpc.existUser                        avgt       3   4.098 ± 0.862   ms/op
ClientGrpc.getUser                          avgt       3   4.317 ± 1.418   ms/op
ClientGrpc.listUser                         avgt       3   5.440 ± 1.614   ms/op
ClientGrpc.createUser                     sample  222075   4.326 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.994           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.997           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.627           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.451           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.185           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.282           ms/op
ClientGrpc.existUser                      sample  240990   3.983 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.372           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.087           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.266           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.862           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.689           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.884           ms/op
ClientGrpc.getUser                        sample  218510   4.392 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.733           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.571           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.988           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.569           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.567           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.266           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.053           ms/op
ClientGrpc.listUser                       sample  167548   5.727 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.186           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.840           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.798           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.420           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.576           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.480           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.766           ms/op
