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
# Warmup Iteration   1: 2.203 ops/ms
# Warmup Iteration   2: 5.320 ops/ms
# Warmup Iteration   3: 6.906 ops/ms
Iteration   1: 7.094 ops/ms
Iteration   2: 7.163 ops/ms
Iteration   3: 6.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.081 ±(99.9%) 1.616 ops/ms [Average]
  (min, avg, max) = (6.987, 7.081, 7.163), stdev = 0.089
  CI (99.9%): [5.465, 8.697] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.660 ops/ms
# Warmup Iteration   2: 7.084 ops/ms
# Warmup Iteration   3: 7.679 ops/ms
Iteration   1: 7.731 ops/ms
Iteration   2: 8.060 ops/ms
Iteration   3: 7.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.890 ±(99.9%) 3.007 ops/ms [Average]
  (min, avg, max) = (7.731, 7.890, 8.060), stdev = 0.165
  CI (99.9%): [4.883, 10.897] (assumes normal distribution)


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
# Warmup Iteration   1: 4.365 ops/ms
# Warmup Iteration   2: 7.035 ops/ms
# Warmup Iteration   3: 7.434 ops/ms
Iteration   1: 7.612 ops/ms
Iteration   2: 7.466 ops/ms
Iteration   3: 7.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.520 ±(99.9%) 1.458 ops/ms [Average]
  (min, avg, max) = (7.466, 7.520, 7.612), stdev = 0.080
  CI (99.9%): [6.062, 8.978] (assumes normal distribution)


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
# Warmup Iteration   1: 3.881 ops/ms
# Warmup Iteration   2: 5.283 ops/ms
# Warmup Iteration   3: 5.900 ops/ms
Iteration   1: 5.691 ops/ms
Iteration   2: 5.752 ops/ms
Iteration   3: 5.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.755 ±(99.9%) 1.205 ops/ms [Average]
  (min, avg, max) = (5.691, 5.755, 5.823), stdev = 0.066
  CI (99.9%): [4.551, 6.960] (assumes normal distribution)


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
# Warmup Iteration   1: 6.793 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.738 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.525 ±(99.9%) 0.004 ms/op
Iteration   1: 4.304 ±(99.9%) 0.005 ms/op
Iteration   2: 4.323 ±(99.9%) 0.004 ms/op
Iteration   3: 4.312 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.313 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (4.304, 4.313, 4.323), stdev = 0.009
  CI (99.9%): [4.143, 4.483] (assumes normal distribution)


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
# Warmup Iteration   1: 5.983 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.003 ms/op
Iteration   1: 4.186 ±(99.9%) 0.002 ms/op
Iteration   2: 4.129 ±(99.9%) 0.003 ms/op
Iteration   3: 4.176 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.164 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (4.129, 4.164, 4.186), stdev = 0.030
  CI (99.9%): [3.608, 4.719] (assumes normal distribution)


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
# Warmup Iteration   1: 6.027 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.740 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.591 ±(99.9%) 0.014 ms/op
Iteration   1: 4.378 ±(99.9%) 0.003 ms/op
Iteration   2: 4.428 ±(99.9%) 0.004 ms/op
Iteration   3: 4.344 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.383 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (4.344, 4.383, 4.428), stdev = 0.042
  CI (99.9%): [3.609, 5.158] (assumes normal distribution)


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
# Warmup Iteration   1: 7.322 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 6.069 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.609 ±(99.9%) 0.020 ms/op
Iteration   1: 5.526 ±(99.9%) 0.016 ms/op
Iteration   2: 5.623 ±(99.9%) 0.019 ms/op
Iteration   3: 5.683 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.611 ±(99.9%) 1.445 ms/op [Average]
  (min, avg, max) = (5.526, 5.611, 5.683), stdev = 0.079
  CI (99.9%): [4.166, 7.056] (assumes normal distribution)


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
# Warmup Iteration   1: 7.195 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.692 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.477 ±(99.9%) 0.015 ms/op
Iteration   1: 4.271 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.625 ms/op
                 createUser·p0.50:   4.182 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   7.852 ms/op
                 createUser·p0.999:  13.451 ms/op
                 createUser·p0.9999: 24.986 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   2: 4.243 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   4.170 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  12.371 ms/op
                 createUser·p0.9999: 27.343 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   3: 4.305 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   4.186 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.816 ms/op
                 createUser·p0.99:   7.938 ms/op
                 createUser·p0.999:  22.077 ms/op
                 createUser·p0.9999: 28.958 ms/op
                 createUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224688
  mean =      4.273 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6600 
    [ 2.500,  5.000) = 185802 
    [ 5.000,  7.500) = 30024 
    [ 7.500, 10.000) = 1475 
    [10.000, 12.500) = 393 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      4.182 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     15.432 ms/op
     p(99.9900) =     28.427 ms/op
     p(99.9990) =     31.990 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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
# Warmup Iteration   1: 6.003 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.011 ms/op
Iteration   1: 4.062 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   7.201 ms/op
                 existUser·p0.999:  12.806 ms/op
                 existUser·p0.9999: 22.315 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 4.109 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.054 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   7.528 ms/op
                 existUser·p0.999:  14.966 ms/op
                 existUser·p0.9999: 25.337 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 4.136 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   4.026 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   6.712 ms/op
                 existUser·p0.999:  10.924 ms/op
                 existUser·p0.9999: 19.265 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 233953
  mean =      4.102 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5739 
    [ 2.500,  5.000) = 204522 
    [ 5.000,  7.500) = 21649 
    [ 7.500, 10.000) = 1531 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     25.537 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 6.552 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.771 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.395 ±(99.9%) 0.012 ms/op
Iteration   1: 4.423 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   5.947 ms/op
                 getUser·p0.99:   8.118 ms/op
                 getUser·p0.999:  15.478 ms/op
                 getUser·p0.9999: 26.076 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   2: 4.394 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   5.988 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  15.188 ms/op
                 getUser·p0.9999: 19.408 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   3: 4.452 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   5.947 ms/op
                 getUser·p0.99:   7.627 ms/op
                 getUser·p0.999:  12.829 ms/op
                 getUser·p0.9999: 21.949 ms/op
                 getUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216983
  mean =      4.423 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4402 
    [ 2.500,  5.000) = 168712 
    [ 5.000,  7.500) = 41017 
    [ 7.500, 10.000) = 2019 
    [10.000, 12.500) = 473 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     25.438 ms/op
     p(99.9990) =     26.394 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 9.066 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 5.799 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.504 ±(99.9%) 0.016 ms/op
Iteration   1: 5.521 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.518 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  17.110 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   2: 5.622 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.823 ms/op
                 listUser·p0.50:   5.341 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   8.317 ms/op
                 listUser·p0.99:   10.469 ms/op
                 listUser·p0.999:  17.387 ms/op
                 listUser·p0.9999: 21.113 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 5.485 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   5.259 ms/op
                 listUser·p0.90:   6.930 ms/op
                 listUser·p0.95:   7.905 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 22.048 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173125
  mean =      5.542 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 118 
    [ 2.500,  5.000) = 59522 
    [ 5.000,  7.500) = 100626 
    [ 7.500, 10.000) = 10994 
    [10.000, 12.500) = 1358 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.053 ms/op
     p(95.0000) =      8.069 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     22.716 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.081 ± 1.616  ops/ms
ClientGrpc.existUser                       thrpt       3   7.890 ± 3.007  ops/ms
ClientGrpc.getUser                         thrpt       3   7.520 ± 1.458  ops/ms
ClientGrpc.listUser                        thrpt       3   5.755 ± 1.205  ops/ms
ClientGrpc.createUser                       avgt       3   4.313 ± 0.170   ms/op
ClientGrpc.existUser                        avgt       3   4.164 ± 0.556   ms/op
ClientGrpc.getUser                          avgt       3   4.383 ± 0.775   ms/op
ClientGrpc.listUser                         avgt       3   5.611 ± 1.445   ms/op
ClientGrpc.createUser                     sample  224688   4.273 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.625           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.182           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.243           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.751           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.512           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.432           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.427           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.080           ms/op
ClientGrpc.existUser                      sample  233953   4.102 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.079           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.005           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.399           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.217           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.386           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.838           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.559           ms/op
ClientGrpc.getUser                        sample  216983   4.423 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.077           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.497           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.964           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.126           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.877           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.438           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.509           ms/op
ClientGrpc.listUser                       sample  173125   5.542 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.518           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.069           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.093           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.727           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.234           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.003           ms/op
