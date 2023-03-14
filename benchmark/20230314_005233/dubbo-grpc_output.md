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
# Warmup Iteration   1: 2.708 ops/ms
# Warmup Iteration   2: 6.787 ops/ms
# Warmup Iteration   3: 8.183 ops/ms
Iteration   1: 8.336 ops/ms
Iteration   2: 7.691 ops/ms
Iteration   3: 7.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.946 ±(99.9%) 6.254 ops/ms [Average]
  (min, avg, max) = (7.691, 7.946, 8.336), stdev = 0.343
  CI (99.9%): [1.692, 14.199] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 5.564 ops/ms
# Warmup Iteration   2: 8.391 ops/ms
# Warmup Iteration   3: 9.090 ops/ms
Iteration   1: 8.998 ops/ms
Iteration   2: 8.884 ops/ms
Iteration   3: 9.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.984 ±(99.9%) 1.732 ops/ms [Average]
  (min, avg, max) = (8.884, 8.984, 9.072), stdev = 0.095
  CI (99.9%): [7.253, 10.716] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 4.759 ops/ms
# Warmup Iteration   2: 7.245 ops/ms
# Warmup Iteration   3: 7.809 ops/ms
Iteration   1: 7.471 ops/ms
Iteration   2: 7.864 ops/ms
Iteration   3: 7.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.515 ±(99.9%) 6.016 ops/ms [Average]
  (min, avg, max) = (7.209, 7.515, 7.864), stdev = 0.330
  CI (99.9%): [1.499, 13.531] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.034 ops/ms
# Warmup Iteration   2: 4.461 ops/ms
# Warmup Iteration   3: 4.761 ops/ms
Iteration   1: 4.780 ops/ms
Iteration   2: 4.697 ops/ms
Iteration   3: 4.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.808 ±(99.9%) 2.325 ops/ms [Average]
  (min, avg, max) = (4.697, 4.808, 4.947), stdev = 0.127
  CI (99.9%): [2.483, 7.133] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.508 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.300 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.230 ±(99.9%) 0.031 ms/op
Iteration   1: 4.761 ±(99.9%) 0.004 ms/op
Iteration   2: 4.978 ±(99.9%) 0.003 ms/op
Iteration   3: 4.990 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.910 ±(99.9%) 2.353 ms/op [Average]
  (min, avg, max) = (4.761, 4.910, 4.990), stdev = 0.129
  CI (99.9%): [2.557, 7.263] (assumes normal distribution)


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
# Warmup Iteration   1: 6.124 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.003 ms/op
Iteration   1: 4.124 ±(99.9%) 0.004 ms/op
Iteration   2: 4.461 ±(99.9%) 0.005 ms/op
Iteration   3: 4.607 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.397 ±(99.9%) 4.519 ms/op [Average]
  (min, avg, max) = (4.124, 4.397, 4.607), stdev = 0.248
  CI (99.9%): [≈ 0, 8.916] (assumes normal distribution)


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
# Warmup Iteration   1: 7.861 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.603 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.280 ±(99.9%) 0.007 ms/op
Iteration   1: 5.323 ±(99.9%) 0.007 ms/op
Iteration   2: 4.627 ±(99.9%) 0.004 ms/op
Iteration   3: 5.011 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.987 ±(99.9%) 6.357 ms/op [Average]
  (min, avg, max) = (4.627, 4.987, 5.323), stdev = 0.348
  CI (99.9%): [≈ 0, 11.344] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.033 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 7.592 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 6.650 ±(99.9%) 0.026 ms/op
Iteration   1: 6.537 ±(99.9%) 0.023 ms/op
Iteration   2: 6.353 ±(99.9%) 0.019 ms/op
Iteration   3: 6.321 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.403 ±(99.9%) 2.127 ms/op [Average]
  (min, avg, max) = (6.321, 6.403, 6.537), stdev = 0.117
  CI (99.9%): [4.277, 8.530] (assumes normal distribution)


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
# Warmup Iteration   1: 6.518 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 4.408 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.344 ±(99.9%) 0.012 ms/op
Iteration   1: 4.365 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.587 ms/op
                 createUser·p0.95:   6.193 ms/op
                 createUser·p0.99:   8.298 ms/op
                 createUser·p0.999:  14.653 ms/op
                 createUser·p0.9999: 26.281 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   2: 4.412 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   7.823 ms/op
                 createUser·p0.999:  10.913 ms/op
                 createUser·p0.9999: 30.900 ms/op
                 createUser·p1.00:   31.359 ms/op

Iteration   3: 4.259 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   4.157 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  12.025 ms/op
                 createUser·p0.9999: 18.547 ms/op
                 createUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 220816
  mean =      4.345 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4176 
    [ 2.500,  5.000) = 175301 
    [ 5.000,  7.500) = 38637 
    [ 7.500, 10.000) = 2246 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     11.786 ms/op
     p(99.9900) =     30.169 ms/op
     p(99.9990) =     31.221 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.424 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.011 ms/op
Iteration   1: 3.956 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.186 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  8.864 ms/op
                 existUser·p0.9999: 17.882 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   2: 4.052 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  12.832 ms/op
                 existUser·p0.9999: 18.423 ms/op
                 existUser·p1.00:   19.005 ms/op

Iteration   3: 3.909 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.292 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  10.092 ms/op
                 existUser·p0.9999: 27.132 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 241723
  mean =      3.971 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6915 
    [ 2.500,  5.000) = 213918 
    [ 5.000,  7.500) = 19674 
    [ 7.500, 10.000) = 926 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     10.785 ms/op
     p(99.9900) =     25.226 ms/op
     p(99.9990) =     28.243 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.922 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.311 ±(99.9%) 0.012 ms/op
Iteration   1: 4.271 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   4.157 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   7.432 ms/op
                 getUser·p0.999:  10.311 ms/op
                 getUser·p0.9999: 19.990 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   2: 4.283 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  13.130 ms/op
                 getUser·p0.9999: 19.224 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   3: 4.255 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   4.162 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   5.587 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  13.742 ms/op
                 getUser·p0.9999: 21.003 ms/op
                 getUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 224763
  mean =      4.270 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1795 
    [ 2.500,  5.000) = 187924 
    [ 5.000,  7.500) = 33299 
    [ 7.500, 10.000) = 1261 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      4.174 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     12.206 ms/op
     p(99.9900) =     20.301 ms/op
     p(99.9990) =     24.232 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.466 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 5.958 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.604 ±(99.9%) 0.021 ms/op
Iteration   1: 5.198 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   6.554 ms/op
                 listUser·p0.95:   7.455 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  15.202 ms/op
                 listUser·p0.9999: 20.508 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 5.437 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   5.226 ms/op
                 listUser·p0.90:   6.799 ms/op
                 listUser·p0.95:   7.799 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  19.305 ms/op
                 listUser·p0.9999: 27.041 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   3: 5.502 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   6.791 ms/op
                 listUser·p0.95:   7.791 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  18.632 ms/op
                 listUser·p0.9999: 23.637 ms/op
                 listUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 178536
  mean =      5.376 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 125 
    [ 2.500,  5.000) = 72912 
    [ 5.000,  7.500) = 95330 
    [ 7.500, 10.000) = 8659 
    [10.000, 12.500) = 1057 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      6.712 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     27.467 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.946 ± 6.254  ops/ms
ClientGrpc.existUser                       thrpt       3   8.984 ± 1.732  ops/ms
ClientGrpc.getUser                         thrpt       3   7.515 ± 6.016  ops/ms
ClientGrpc.listUser                        thrpt       3   4.808 ± 2.325  ops/ms
ClientGrpc.createUser                       avgt       3   4.910 ± 2.353   ms/op
ClientGrpc.existUser                        avgt       3   4.397 ± 4.519   ms/op
ClientGrpc.getUser                          avgt       3   4.987 ± 6.357   ms/op
ClientGrpc.listUser                         avgt       3   6.403 ± 2.127   ms/op
ClientGrpc.createUser                     sample  220816   4.345 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.928           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.439           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.939           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.791           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.786           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.169           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.359           ms/op
ClientGrpc.existUser                      sample  241723   3.971 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.872           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.899           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.923           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.300           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.521           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.785           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.226           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.344           ms/op
ClientGrpc.getUser                        sample  224763   4.270 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.737           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.174           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.251           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.628           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.070           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.206           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.301           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.347           ms/op
ClientGrpc.listUser                       sample  178536   5.376 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.208           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.712           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.676           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.781           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.596           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.345           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.492           ms/op
