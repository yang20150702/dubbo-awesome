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
# Warmup Iteration   1: 2.111 ops/ms
# Warmup Iteration   2: 5.294 ops/ms
# Warmup Iteration   3: 6.807 ops/ms
Iteration   1: 6.924 ops/ms
Iteration   2: 7.184 ops/ms
Iteration   3: 7.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.073 ±(99.9%) 2.451 ops/ms [Average]
  (min, avg, max) = (6.924, 7.073, 7.184), stdev = 0.134
  CI (99.9%): [4.622, 9.523] (assumes normal distribution)


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
# Warmup Iteration   1: 4.652 ops/ms
# Warmup Iteration   2: 7.239 ops/ms
# Warmup Iteration   3: 7.606 ops/ms
Iteration   1: 8.141 ops/ms
Iteration   2: 7.731 ops/ms
Iteration   3: 7.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.889 ±(99.9%) 4.029 ops/ms [Average]
  (min, avg, max) = (7.731, 7.889, 8.141), stdev = 0.221
  CI (99.9%): [3.859, 11.918] (assumes normal distribution)


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
# Warmup Iteration   1: 3.771 ops/ms
# Warmup Iteration   2: 6.357 ops/ms
# Warmup Iteration   3: 7.008 ops/ms
Iteration   1: 7.164 ops/ms
Iteration   2: 7.300 ops/ms
Iteration   3: 7.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.236 ±(99.9%) 1.246 ops/ms [Average]
  (min, avg, max) = (7.164, 7.236, 7.300), stdev = 0.068
  CI (99.9%): [5.990, 8.482] (assumes normal distribution)


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
# Warmup Iteration   1: 3.600 ops/ms
# Warmup Iteration   2: 4.974 ops/ms
# Warmup Iteration   3: 5.420 ops/ms
Iteration   1: 5.424 ops/ms
Iteration   2: 5.683 ops/ms
Iteration   3: 5.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.652 ±(99.9%) 3.894 ops/ms [Average]
  (min, avg, max) = (5.424, 5.652, 5.848), stdev = 0.213
  CI (99.9%): [1.758, 9.545] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.908 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.629 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.417 ±(99.9%) 0.012 ms/op
Iteration   1: 4.268 ±(99.9%) 0.003 ms/op
Iteration   2: 4.165 ±(99.9%) 0.004 ms/op
Iteration   3: 4.194 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.209 ±(99.9%) 0.973 ms/op [Average]
  (min, avg, max) = (4.165, 4.209, 4.268), stdev = 0.053
  CI (99.9%): [3.236, 5.183] (assumes normal distribution)


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
# Warmup Iteration   1: 6.135 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.496 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.202 ±(99.9%) 0.005 ms/op
Iteration   1: 4.153 ±(99.9%) 0.004 ms/op
Iteration   2: 4.058 ±(99.9%) 0.003 ms/op
Iteration   3: 4.011 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.074 ±(99.9%) 1.319 ms/op [Average]
  (min, avg, max) = (4.011, 4.074, 4.153), stdev = 0.072
  CI (99.9%): [2.755, 5.393] (assumes normal distribution)


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
# Warmup Iteration   1: 6.715 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.587 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.344 ±(99.9%) 0.006 ms/op
Iteration   1: 4.279 ±(99.9%) 0.006 ms/op
Iteration   2: 4.291 ±(99.9%) 0.004 ms/op
Iteration   3: 4.358 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.309 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (4.279, 4.309, 4.358), stdev = 0.042
  CI (99.9%): [3.539, 5.080] (assumes normal distribution)


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
# Warmup Iteration   1: 8.202 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 6.152 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.694 ±(99.9%) 0.019 ms/op
Iteration   1: 5.502 ±(99.9%) 0.011 ms/op
Iteration   2: 5.724 ±(99.9%) 0.019 ms/op
Iteration   3: 5.727 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.651 ±(99.9%) 2.356 ms/op [Average]
  (min, avg, max) = (5.502, 5.651, 5.727), stdev = 0.129
  CI (99.9%): [3.295, 8.007] (assumes normal distribution)


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
# Warmup Iteration   1: 6.891 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.217 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.472 ±(99.9%) 0.014 ms/op
Iteration   1: 4.409 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.423 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   7.168 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 25.092 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   2: 4.440 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.472 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  9.944 ms/op
                 createUser·p0.9999: 28.429 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   3: 4.487 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   4.399 ms/op
                 createUser·p0.90:   5.669 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   7.528 ms/op
                 createUser·p0.999:  26.608 ms/op
                 createUser·p0.9999: 31.252 ms/op
                 createUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215967
  mean =      4.445 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4451 
    [ 2.500,  5.000) = 164821 
    [ 5.000,  7.500) = 44847 
    [ 7.500, 10.000) = 1402 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     12.944 ms/op
     p(99.9900) =     29.603 ms/op
     p(99.9990) =     31.654 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 5.471 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.426 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.011 ms/op
Iteration   1: 4.126 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   4.039 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   6.963 ms/op
                 existUser·p0.999:  12.365 ms/op
                 existUser·p0.9999: 14.347 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   2: 4.060 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   3.994 ms/op
                 existUser·p0.90:   4.932 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   7.815 ms/op
                 existUser·p0.999:  14.612 ms/op
                 existUser·p0.9999: 31.949 ms/op
                 existUser·p1.00:   32.440 ms/op

Iteration   3: 4.117 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   6.914 ms/op
                 existUser·p0.999:  10.151 ms/op
                 existUser·p0.9999: 25.803 ms/op
                 existUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 234140
  mean =      4.101 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7831 
    [ 2.500,  5.000) = 201042 
    [ 5.000,  7.500) = 23218 
    [ 7.500, 10.000) = 1531 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     12.939 ms/op
     p(99.9900) =     31.149 ms/op
     p(99.9990) =     32.341 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 6.526 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.505 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.290 ±(99.9%) 0.013 ms/op
Iteration   1: 4.435 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.489 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   7.717 ms/op
                 getUser·p0.999:  12.515 ms/op
                 getUser·p0.9999: 18.500 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   2: 4.503 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   4.391 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.256 ms/op
                 getUser·p0.999:  10.240 ms/op
                 getUser·p0.9999: 20.244 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   3: 4.359 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   4.231 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   7.938 ms/op
                 getUser·p0.999:  14.765 ms/op
                 getUser·p0.9999: 22.577 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216507
  mean =      4.431 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3786 
    [ 2.500,  5.000) = 166485 
    [ 5.000,  7.500) = 43901 
    [ 7.500, 10.000) = 1829 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.554 ms/op
     p(95.0000) =      6.001 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     12.533 ms/op
     p(99.9900) =     21.835 ms/op
     p(99.9990) =     23.151 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 8.396 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 6.327 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.899 ±(99.9%) 0.021 ms/op
Iteration   1: 5.903 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   5.628 ms/op
                 listUser·p0.90:   7.815 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   11.125 ms/op
                 listUser·p0.999:  16.608 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 5.741 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  20.021 ms/op
                 listUser·p0.9999: 32.776 ms/op
                 listUser·p1.00:   38.863 ms/op

Iteration   3: 5.708 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.397 ms/op
                 listUser·p0.95:   8.380 ms/op
                 listUser·p0.99:   10.813 ms/op
                 listUser·p0.999:  19.919 ms/op
                 listUser·p0.9999: 26.212 ms/op
                 listUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166285
  mean =      5.783 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 123 
    [ 2.500,  5.000) = 49687 
    [ 5.000,  7.500) = 98466 
    [ 7.500, 10.000) = 14946 
    [10.000, 12.500) = 2413 
    [12.500, 15.000) = 347 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.610 ms/op
     p(95.0000) =      8.520 ms/op
     p(99.0000) =     10.863 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     31.801 ms/op
     p(99.9990) =     38.776 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.073 ± 2.451  ops/ms
ClientGrpc.existUser                       thrpt       3   7.889 ± 4.029  ops/ms
ClientGrpc.getUser                         thrpt       3   7.236 ± 1.246  ops/ms
ClientGrpc.listUser                        thrpt       3   5.652 ± 3.894  ops/ms
ClientGrpc.createUser                       avgt       3   4.209 ± 0.973   ms/op
ClientGrpc.existUser                        avgt       3   4.074 ± 1.319   ms/op
ClientGrpc.getUser                          avgt       3   4.309 ± 0.770   ms/op
ClientGrpc.listUser                         avgt       3   5.651 ± 2.356   ms/op
ClientGrpc.createUser                     sample  215967   4.445 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.027           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.931           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.242           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.944           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.603           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.719           ms/op
ClientGrpc.existUser                      sample  234140   4.101 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.612           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.046           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.505           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.234           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.939           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.149           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.440           ms/op
ClientGrpc.getUser                        sample  216507   4.431 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.104           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.554           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.001           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.610           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.533           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.835           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.364           ms/op
ClientGrpc.listUser                       sample  166285   5.783 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.098           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.610           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.863           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.104           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.801           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.863           ms/op
