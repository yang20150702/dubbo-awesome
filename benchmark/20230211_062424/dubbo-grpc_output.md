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
# Warmup Iteration   1: 2.389 ops/ms
# Warmup Iteration   2: 5.696 ops/ms
# Warmup Iteration   3: 6.919 ops/ms
Iteration   1: 7.528 ops/ms
Iteration   2: 7.413 ops/ms
Iteration   3: 7.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.393 ±(99.9%) 2.658 ops/ms [Average]
  (min, avg, max) = (7.239, 7.393, 7.528), stdev = 0.146
  CI (99.9%): [4.735, 10.052] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.936 ops/ms
# Warmup Iteration   2: 7.352 ops/ms
# Warmup Iteration   3: 7.885 ops/ms
Iteration   1: 7.585 ops/ms
Iteration   2: 7.683 ops/ms
Iteration   3: 7.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.648 ±(99.9%) 1.003 ops/ms [Average]
  (min, avg, max) = (7.585, 7.648, 7.683), stdev = 0.055
  CI (99.9%): [6.645, 8.652] (assumes normal distribution)


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
# Warmup Iteration   1: 4.588 ops/ms
# Warmup Iteration   2: 6.741 ops/ms
# Warmup Iteration   3: 7.353 ops/ms
Iteration   1: 7.536 ops/ms
Iteration   2: 7.596 ops/ms
Iteration   3: 7.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.477 ±(99.9%) 2.862 ops/ms [Average]
  (min, avg, max) = (7.299, 7.477, 7.596), stdev = 0.157
  CI (99.9%): [4.615, 10.339] (assumes normal distribution)


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
# Warmup Iteration   1: 3.826 ops/ms
# Warmup Iteration   2: 5.434 ops/ms
# Warmup Iteration   3: 5.871 ops/ms
Iteration   1: 6.070 ops/ms
Iteration   2: 5.762 ops/ms
Iteration   3: 6.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.951 ±(99.9%) 3.017 ops/ms [Average]
  (min, avg, max) = (5.762, 5.951, 6.070), stdev = 0.165
  CI (99.9%): [2.934, 8.968] (assumes normal distribution)


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
# Warmup Iteration   1: 7.267 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.506 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.324 ±(99.9%) 0.004 ms/op
Iteration   1: 4.339 ±(99.9%) 0.005 ms/op
Iteration   2: 4.300 ±(99.9%) 0.002 ms/op
Iteration   3: 4.245 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.294 ±(99.9%) 0.862 ms/op [Average]
  (min, avg, max) = (4.245, 4.294, 4.339), stdev = 0.047
  CI (99.9%): [3.432, 5.157] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.056 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.003 ms/op
Iteration   1: 4.101 ±(99.9%) 0.005 ms/op
Iteration   2: 3.989 ±(99.9%) 0.004 ms/op
Iteration   3: 4.063 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.051 ±(99.9%) 1.040 ms/op [Average]
  (min, avg, max) = (3.989, 4.051, 4.101), stdev = 0.057
  CI (99.9%): [3.011, 5.091] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.465 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.510 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.430 ±(99.9%) 0.004 ms/op
Iteration   1: 4.405 ±(99.9%) 0.003 ms/op
Iteration   2: 4.421 ±(99.9%) 0.005 ms/op
Iteration   3: 4.434 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.420 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (4.405, 4.420, 4.434), stdev = 0.015
  CI (99.9%): [4.155, 4.685] (assumes normal distribution)


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
# Warmup Iteration   1: 7.750 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.954 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.451 ±(99.9%) 0.014 ms/op
Iteration   1: 5.310 ±(99.9%) 0.009 ms/op
Iteration   2: 5.408 ±(99.9%) 0.007 ms/op
Iteration   3: 5.252 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.323 ±(99.9%) 1.439 ms/op [Average]
  (min, avg, max) = (5.252, 5.323, 5.408), stdev = 0.079
  CI (99.9%): [3.884, 6.762] (assumes normal distribution)


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
# Warmup Iteration   1: 6.646 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.464 ±(99.9%) 0.015 ms/op
Iteration   1: 4.399 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.636 ms/op
                 createUser·p0.95:   6.029 ms/op
                 createUser·p0.99:   8.118 ms/op
                 createUser·p0.999:  12.045 ms/op
                 createUser·p0.9999: 16.347 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   2: 4.395 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   7.406 ms/op
                 createUser·p0.999:  13.134 ms/op
                 createUser·p0.9999: 23.813 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 4.391 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   7.578 ms/op
                 createUser·p0.999:  14.746 ms/op
                 createUser·p0.9999: 23.550 ms/op
                 createUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 218660
  mean =      4.395 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6599 
    [ 2.500,  5.000) = 157315 
    [ 5.000,  7.500) = 52342 
    [ 7.500, 10.000) = 1558 
    [10.000, 12.500) = 564 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     24.138 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 5.631 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.357 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.012 ms/op
Iteration   1: 4.036 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   3.985 ms/op
                 existUser·p0.90:   5.120 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   7.274 ms/op
                 existUser·p0.999:  12.264 ms/op
                 existUser·p0.9999: 23.137 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   2: 4.116 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   4.010 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   7.651 ms/op
                 existUser·p0.999:  12.916 ms/op
                 existUser·p0.9999: 30.421 ms/op
                 existUser·p1.00:   30.867 ms/op

Iteration   3: 4.059 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   3.977 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.546 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  12.853 ms/op
                 existUser·p0.9999: 20.885 ms/op
                 existUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 235758
  mean =      4.070 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10910 
    [ 2.500,  5.000) = 193270 
    [ 5.000,  7.500) = 29466 
    [ 7.500, 10.000) = 1584 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     12.660 ms/op
     p(99.9900) =     29.786 ms/op
     p(99.9990) =     30.790 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 6.121 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.407 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.257 ±(99.9%) 0.013 ms/op
Iteration   1: 4.474 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.160 ms/op
                 getUser·p0.99:   8.317 ms/op
                 getUser·p0.999:  15.172 ms/op
                 getUser·p0.9999: 21.622 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   2: 4.272 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   4.166 ms/op
                 getUser·p0.90:   5.341 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   7.879 ms/op
                 getUser·p0.999:  11.485 ms/op
                 getUser·p0.9999: 19.595 ms/op
                 getUser·p1.00:   19.595 ms/op

Iteration   3: 4.307 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   7.180 ms/op
                 getUser·p0.999:  10.613 ms/op
                 getUser·p0.9999: 21.487 ms/op
                 getUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 220639
  mean =      4.349 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4209 
    [ 2.500,  5.000) = 169795 
    [ 5.000,  7.500) = 43972 
    [ 7.500, 10.000) = 2107 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     21.428 ms/op
     p(99.9990) =     22.151 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.518 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.106 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.570 ±(99.9%) 0.021 ms/op
Iteration   1: 5.361 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.700 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   7.198 ms/op
                 listUser·p0.95:   8.094 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  16.585 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   2: 5.495 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   7.234 ms/op
                 listUser·p0.95:   8.028 ms/op
                 listUser·p0.99:   10.551 ms/op
                 listUser·p0.999:  19.786 ms/op
                 listUser·p0.9999: 23.507 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   3: 5.298 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   5.022 ms/op
                 listUser·p0.90:   7.053 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  22.015 ms/op
                 listUser·p0.9999: 28.339 ms/op
                 listUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 178272
  mean =      5.383 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 303 
    [ 2.500,  5.000) = 80723 
    [ 5.000,  7.500) = 83511 
    [ 7.500, 10.000) = 11536 
    [10.000, 12.500) = 1411 
    [12.500, 15.000) = 292 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      7.168 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     10.371 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     27.307 ms/op
     p(99.9990) =     28.954 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.393 ± 2.658  ops/ms
ClientGrpc.existUser                       thrpt       3   7.648 ± 1.003  ops/ms
ClientGrpc.getUser                         thrpt       3   7.477 ± 2.862  ops/ms
ClientGrpc.listUser                        thrpt       3   5.951 ± 3.017  ops/ms
ClientGrpc.createUser                       avgt       3   4.294 ± 0.862   ms/op
ClientGrpc.existUser                        avgt       3   4.051 ± 1.040   ms/op
ClientGrpc.getUser                          avgt       3   4.420 ± 0.265   ms/op
ClientGrpc.listUser                         avgt       3   5.323 ± 1.439   ms/op
ClientGrpc.createUser                     sample  218660   4.395 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.882           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.005           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.700           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.205           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.527           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.216           ms/op
ClientGrpc.existUser                      sample  235758   4.070 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.899           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.177           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.579           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.266           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.660           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.786           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.867           ms/op
ClientGrpc.getUser                        sample  220639   4.349 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.042           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.497           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.931           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.815           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.845           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.428           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.282           ms/op
ClientGrpc.listUser                       sample  178272   5.383 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.700           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.168           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.020           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.371           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.399           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.307           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.262           ms/op
