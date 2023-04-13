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
# Warmup Iteration   1: 2.371 ops/ms
# Warmup Iteration   2: 5.742 ops/ms
# Warmup Iteration   3: 7.233 ops/ms
Iteration   1: 7.661 ops/ms
Iteration   2: 7.609 ops/ms
Iteration   3: 7.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.640 ±(99.9%) 0.491 ops/ms [Average]
  (min, avg, max) = (7.609, 7.640, 7.661), stdev = 0.027
  CI (99.9%): [7.149, 8.131] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.933 ops/ms
# Warmup Iteration   2: 7.775 ops/ms
# Warmup Iteration   3: 8.291 ops/ms
Iteration   1: 8.366 ops/ms
Iteration   2: 8.489 ops/ms
Iteration   3: 8.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.479 ±(99.9%) 1.966 ops/ms [Average]
  (min, avg, max) = (8.366, 8.479, 8.581), stdev = 0.108
  CI (99.9%): [6.513, 10.444] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.710 ops/ms
# Warmup Iteration   2: 7.204 ops/ms
# Warmup Iteration   3: 7.588 ops/ms
Iteration   1: 7.664 ops/ms
Iteration   2: 7.760 ops/ms
Iteration   3: 7.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.778 ±(99.9%) 2.271 ops/ms [Average]
  (min, avg, max) = (7.664, 7.778, 7.911), stdev = 0.124
  CI (99.9%): [5.507, 10.050] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.082 ops/ms
# Warmup Iteration   2: 5.467 ops/ms
# Warmup Iteration   3: 5.907 ops/ms
Iteration   1: 5.980 ops/ms
Iteration   2: 5.952 ops/ms
Iteration   3: 5.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.959 ±(99.9%) 0.330 ops/ms [Average]
  (min, avg, max) = (5.946, 5.959, 5.980), stdev = 0.018
  CI (99.9%): [5.629, 6.290] (assumes normal distribution)


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
# Warmup Iteration   1: 6.069 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.004 ms/op
Iteration   1: 4.117 ±(99.9%) 0.004 ms/op
Iteration   2: 4.126 ±(99.9%) 0.004 ms/op
Iteration   3: 4.262 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.168 ±(99.9%) 1.479 ms/op [Average]
  (min, avg, max) = (4.117, 4.168, 4.262), stdev = 0.081
  CI (99.9%): [2.689, 5.647] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.141 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.003 ms/op
Iteration   1: 3.925 ±(99.9%) 0.002 ms/op
Iteration   2: 3.826 ±(99.9%) 0.002 ms/op
Iteration   3: 3.792 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.848 ±(99.9%) 1.264 ms/op [Average]
  (min, avg, max) = (3.792, 3.848, 3.925), stdev = 0.069
  CI (99.9%): [2.584, 5.112] (assumes normal distribution)


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
# Warmup Iteration   1: 5.796 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.296 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.003 ms/op
Iteration   1: 4.089 ±(99.9%) 0.005 ms/op
Iteration   2: 4.097 ±(99.9%) 0.003 ms/op
Iteration   3: 4.177 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.121 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (4.089, 4.121, 4.177), stdev = 0.049
  CI (99.9%): [3.234, 5.009] (assumes normal distribution)


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
# Warmup Iteration   1: 7.572 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.728 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.513 ±(99.9%) 0.022 ms/op
Iteration   1: 5.438 ±(99.9%) 0.015 ms/op
Iteration   2: 5.494 ±(99.9%) 0.016 ms/op
Iteration   3: 5.298 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.410 ±(99.9%) 1.842 ms/op [Average]
  (min, avg, max) = (5.298, 5.410, 5.494), stdev = 0.101
  CI (99.9%): [3.568, 7.252] (assumes normal distribution)


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
# Warmup Iteration   1: 6.211 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.329 ±(99.9%) 0.012 ms/op
Iteration   1: 4.147 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.751 ms/op
                 createUser·p0.99:   7.569 ms/op
                 createUser·p0.999:  11.464 ms/op
                 createUser·p0.9999: 16.387 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   2: 4.000 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.965 ms/op
                 createUser·p0.90:   5.186 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  10.566 ms/op
                 createUser·p0.9999: 17.956 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   3: 4.223 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   4.104 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  11.018 ms/op
                 createUser·p0.9999: 21.772 ms/op
                 createUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 232925
  mean =      4.121 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9105 
    [ 2.500,  5.000) = 189401 
    [ 5.000,  7.500) = 32313 
    [ 7.500, 10.000) = 1644 
    [10.000, 12.500) = 301 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     11.108 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     22.545 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 5.710 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.010 ms/op
Iteration   1: 3.849 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  13.805 ms/op
                 existUser·p0.9999: 22.874 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   2: 3.848 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.801 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 18.022 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 3.825 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  9.526 ms/op
                 existUser·p0.9999: 19.855 ms/op
                 existUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 249920
  mean =      3.841 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9122 
    [ 2.500,  5.000) = 224826 
    [ 5.000,  7.500) = 14782 
    [ 7.500, 10.000) = 876 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     10.519 ms/op
     p(99.9900) =     21.988 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 6.350 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.554 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.012 ms/op
Iteration   1: 4.217 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   4.096 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   7.717 ms/op
                 getUser·p0.999:  14.346 ms/op
                 getUser·p0.9999: 17.479 ms/op
                 getUser·p1.00:   17.859 ms/op

Iteration   2: 4.268 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   4.137 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  12.763 ms/op
                 getUser·p0.9999: 17.629 ms/op
                 getUser·p1.00:   18.285 ms/op

Iteration   3: 4.249 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   4.141 ms/op
                 getUser·p0.90:   5.300 ms/op
                 getUser·p0.95:   5.710 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  10.399 ms/op
                 getUser·p0.9999: 29.520 ms/op
                 getUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 226109
  mean =      4.244 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3832 
    [ 2.500,  5.000) = 187531 
    [ 5.000,  7.500) = 32662 
    [ 7.500, 10.000) = 1519 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     12.743 ms/op
     p(99.9900) =     28.579 ms/op
     p(99.9990) =     29.966 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 6.882 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.903 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.458 ±(99.9%) 0.022 ms/op
Iteration   1: 5.442 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   5.079 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.307 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  17.086 ms/op
                 listUser·p0.9999: 25.742 ms/op
                 listUser·p1.00:   26.247 ms/op

Iteration   2: 5.464 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.348 ms/op
                 listUser·p0.99:   10.250 ms/op
                 listUser·p0.999:  19.017 ms/op
                 listUser·p0.9999: 22.741 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   3: 5.381 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   7.971 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  21.384 ms/op
                 listUser·p0.9999: 23.953 ms/op
                 listUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176917
  mean =      5.429 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185 
    [ 2.500,  5.000) = 79144 
    [ 5.000,  7.500) = 82408 
    [ 7.500, 10.000) = 13020 
    [10.000, 12.500) = 1644 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      7.283 ms/op
     p(95.0000) =      8.217 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     18.746 ms/op
     p(99.9900) =     24.725 ms/op
     p(99.9990) =     26.197 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.640 ± 0.491  ops/ms
ClientGrpc.existUser                       thrpt       3   8.479 ± 1.966  ops/ms
ClientGrpc.getUser                         thrpt       3   7.778 ± 2.271  ops/ms
ClientGrpc.listUser                        thrpt       3   5.959 ± 0.330  ops/ms
ClientGrpc.createUser                       avgt       3   4.168 ± 1.479   ms/op
ClientGrpc.existUser                        avgt       3   3.848 ± 1.264   ms/op
ClientGrpc.getUser                          avgt       3   4.121 ± 0.887   ms/op
ClientGrpc.listUser                         avgt       3   5.410 ± 1.842   ms/op
ClientGrpc.createUser                     sample  232925   4.121 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.826           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.022           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.276           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.743           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.348           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.108           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.398           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.577           ms/op
ClientGrpc.existUser                      sample  249920   3.841 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.907           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.751           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.136           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.357           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.519           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.988           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.560           ms/op
ClientGrpc.getUser                        sample  226109   4.244 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.582           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.718           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.348           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.743           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.579           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.081           ms/op
ClientGrpc.listUser                       sample  176917   5.429 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.880           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.283           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.217           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.273           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.746           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.725           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.247           ms/op
