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
# Warmup Iteration   1: 2.401 ops/ms
# Warmup Iteration   2: 5.726 ops/ms
# Warmup Iteration   3: 7.203 ops/ms
Iteration   1: 7.204 ops/ms
Iteration   2: 7.408 ops/ms
Iteration   3: 7.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.266 ±(99.9%) 2.258 ops/ms [Average]
  (min, avg, max) = (7.186, 7.266, 7.408), stdev = 0.124
  CI (99.9%): [5.008, 9.524] (assumes normal distribution)


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
# Warmup Iteration   1: 5.029 ops/ms
# Warmup Iteration   2: 7.059 ops/ms
# Warmup Iteration   3: 7.502 ops/ms
Iteration   1: 7.597 ops/ms
Iteration   2: 7.888 ops/ms
Iteration   3: 7.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.739 ±(99.9%) 2.656 ops/ms [Average]
  (min, avg, max) = (7.597, 7.739, 7.888), stdev = 0.146
  CI (99.9%): [5.083, 10.395] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.529 ops/ms
# Warmup Iteration   2: 7.159 ops/ms
# Warmup Iteration   3: 7.082 ops/ms
Iteration   1: 7.268 ops/ms
Iteration   2: 7.283 ops/ms
Iteration   3: 7.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.211 ±(99.9%) 2.032 ops/ms [Average]
  (min, avg, max) = (7.083, 7.211, 7.283), stdev = 0.111
  CI (99.9%): [5.179, 9.244] (assumes normal distribution)


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
# Warmup Iteration   1: 3.820 ops/ms
# Warmup Iteration   2: 5.302 ops/ms
# Warmup Iteration   3: 5.811 ops/ms
Iteration   1: 5.948 ops/ms
Iteration   2: 5.882 ops/ms
Iteration   3: 6.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.015 ±(99.9%) 3.206 ops/ms [Average]
  (min, avg, max) = (5.882, 6.015, 6.214), stdev = 0.176
  CI (99.9%): [2.809, 9.221] (assumes normal distribution)


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
# Warmup Iteration   1: 6.230 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.310 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.010 ms/op
Iteration   1: 4.244 ±(99.9%) 0.005 ms/op
Iteration   2: 4.335 ±(99.9%) 0.002 ms/op
Iteration   3: 4.380 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.320 ±(99.9%) 1.264 ms/op [Average]
  (min, avg, max) = (4.244, 4.320, 4.380), stdev = 0.069
  CI (99.9%): [3.056, 5.584] (assumes normal distribution)


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
# Warmup Iteration   1: 5.971 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.003 ms/op
Iteration   1: 4.104 ±(99.9%) 0.003 ms/op
Iteration   2: 4.123 ±(99.9%) 0.003 ms/op
Iteration   3: 4.169 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.132 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (4.104, 4.132, 4.169), stdev = 0.033
  CI (99.9%): [3.522, 4.743] (assumes normal distribution)


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
# Warmup Iteration   1: 6.171 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.450 ±(99.9%) 0.004 ms/op
Iteration   1: 4.182 ±(99.9%) 0.002 ms/op
Iteration   2: 4.376 ±(99.9%) 0.003 ms/op
Iteration   3: 4.408 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.322 ±(99.9%) 2.234 ms/op [Average]
  (min, avg, max) = (4.182, 4.322, 4.408), stdev = 0.122
  CI (99.9%): [2.087, 6.556] (assumes normal distribution)


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
# Warmup Iteration   1: 8.187 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.600 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.560 ±(99.9%) 0.012 ms/op
Iteration   1: 5.378 ±(99.9%) 0.013 ms/op
Iteration   2: 5.302 ±(99.9%) 0.010 ms/op
Iteration   3: 5.332 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.337 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (5.302, 5.337, 5.378), stdev = 0.038
  CI (99.9%): [4.640, 6.034] (assumes normal distribution)


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
# Warmup Iteration   1: 6.562 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.903 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.425 ±(99.9%) 0.014 ms/op
Iteration   1: 4.361 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  11.616 ms/op
                 createUser·p0.9999: 19.912 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   2: 4.354 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   7.176 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 22.949 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   3: 4.362 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.562 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   7.825 ms/op
                 createUser·p0.999:  23.885 ms/op
                 createUser·p0.9999: 28.934 ms/op
                 createUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219963
  mean =      4.359 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3387 
    [ 2.500,  5.000) = 166359 
    [ 5.000,  7.500) = 48236 
    [ 7.500, 10.000) = 1452 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     28.770 ms/op
     p(99.9990) =     28.934 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 5.978 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.429 ±(99.9%) 0.015 ms/op
Iteration   1: 4.377 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   4.268 ms/op
                 existUser·p0.90:   5.571 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   7.381 ms/op
                 existUser·p0.999:  10.322 ms/op
                 existUser·p0.9999: 17.347 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   2: 4.325 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.480 ms/op
                 existUser·p0.95:   5.865 ms/op
                 existUser·p0.99:   7.217 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 17.433 ms/op
                 existUser·p1.00:   17.957 ms/op

Iteration   3: 4.128 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   4.043 ms/op
                 existUser·p0.90:   5.218 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  13.444 ms/op
                 existUser·p0.9999: 26.083 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 224487
  mean =      4.274 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4814 
    [ 2.500,  5.000) = 175055 
    [ 5.000,  7.500) = 42875 
    [ 7.500, 10.000) = 1405 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      4.174 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.161 ms/op
     p(99.9000) =     11.616 ms/op
     p(99.9900) =     23.742 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 6.502 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.701 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.546 ±(99.9%) 0.013 ms/op
Iteration   1: 4.461 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.661 ms/op
                 getUser·p0.95:   6.169 ms/op
                 getUser·p0.99:   8.012 ms/op
                 getUser·p0.999:  20.323 ms/op
                 getUser·p0.9999: 25.113 ms/op
                 getUser·p1.00:   39.453 ms/op

Iteration   2: 4.353 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   5.947 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  16.766 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   3: 4.356 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   5.988 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  11.596 ms/op
                 getUser·p0.9999: 31.992 ms/op
                 getUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218651
  mean =      4.389 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4629 
    [ 2.500,  5.000) = 167253 
    [ 5.000,  7.500) = 44309 
    [ 7.500, 10.000) = 1839 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     15.429 ms/op
     p(99.9900) =     29.926 ms/op
     p(99.9990) =     32.955 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


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
# Warmup Iteration   1: 8.091 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.837 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.437 ±(99.9%) 0.018 ms/op
Iteration   1: 5.537 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.365 ms/op
                 listUser·p0.95:   8.176 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 19.733 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   2: 5.626 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.234 ms/op
                 listUser·p0.95:   8.033 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  17.345 ms/op
                 listUser·p0.9999: 21.298 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 5.651 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.545 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  23.243 ms/op
                 listUser·p0.9999: 32.200 ms/op
                 listUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171358
  mean =      5.604 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 124 
    [ 2.500,  5.000) = 62250 
    [ 5.000,  7.500) = 93449 
    [ 7.500, 10.000) = 13132 
    [10.000, 12.500) = 1696 
    [12.500, 15.000) = 368 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      5.317 ms/op
     p(90.0000) =      7.373 ms/op
     p(95.0000) =      8.233 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     29.187 ms/op
     p(99.9990) =     32.553 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.266 ± 2.258  ops/ms
ClientGrpc.existUser                       thrpt       3   7.739 ± 2.656  ops/ms
ClientGrpc.getUser                         thrpt       3   7.211 ± 2.032  ops/ms
ClientGrpc.listUser                        thrpt       3   6.015 ± 3.206  ops/ms
ClientGrpc.createUser                       avgt       3   4.320 ± 1.264   ms/op
ClientGrpc.existUser                        avgt       3   4.132 ± 0.610   ms/op
ClientGrpc.getUser                          avgt       3   4.322 ± 2.234   ms/op
ClientGrpc.listUser                         avgt       3   5.337 ± 0.697   ms/op
ClientGrpc.createUser                     sample  219963   4.359 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.931           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.562           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.964           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.356           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.533           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.770           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.934           ms/op
ClientGrpc.existUser                      sample  224487   4.274 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.808           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.448           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.833           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.161           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.616           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.742           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.837           ms/op
ClientGrpc.getUser                        sample  218651   4.389 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.910           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.562           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.038           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.635           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.429           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.926           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          39.453           ms/op
ClientGrpc.listUser                       sample  171358   5.604 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.337           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.317           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.233           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.584           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.022           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.187           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.670           ms/op
