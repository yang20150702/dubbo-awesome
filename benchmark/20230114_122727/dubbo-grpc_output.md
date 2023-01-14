# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.447 ops/ms
# Warmup Iteration   2: 6.160 ops/ms
# Warmup Iteration   3: 7.191 ops/ms
Iteration   1: 7.535 ops/ms
Iteration   2: 7.400 ops/ms
Iteration   3: 7.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.504 ±(99.9%) 1.691 ops/ms [Average]
  (min, avg, max) = (7.400, 7.504, 7.577), stdev = 0.093
  CI (99.9%): [5.813, 9.195] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.843 ops/ms
# Warmup Iteration   2: 7.070 ops/ms
# Warmup Iteration   3: 7.470 ops/ms
Iteration   1: 7.592 ops/ms
Iteration   2: 7.773 ops/ms
Iteration   3: 7.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.641 ±(99.9%) 2.106 ops/ms [Average]
  (min, avg, max) = (7.558, 7.641, 7.773), stdev = 0.115
  CI (99.9%): [5.535, 9.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ops/ms
# Warmup Iteration   2: 6.670 ops/ms
# Warmup Iteration   3: 7.267 ops/ms
Iteration   1: 7.464 ops/ms
Iteration   2: 7.636 ops/ms
Iteration   3: 7.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.497 ±(99.9%) 2.295 ops/ms [Average]
  (min, avg, max) = (7.391, 7.497, 7.636), stdev = 0.126
  CI (99.9%): [5.202, 9.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ops/ms
# Warmup Iteration   2: 5.744 ops/ms
# Warmup Iteration   3: 5.946 ops/ms
Iteration   1: 6.169 ops/ms
Iteration   2: 6.179 ops/ms
Iteration   3: 6.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.190 ±(99.9%) 0.501 ops/ms [Average]
  (min, avg, max) = (6.169, 6.190, 6.221), stdev = 0.027
  CI (99.9%): [5.689, 6.691] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.316 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.389 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.003 ms/op
Iteration   1: 4.355 ±(99.9%) 0.002 ms/op
Iteration   2: 4.274 ±(99.9%) 0.003 ms/op
Iteration   3: 4.271 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.300 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (4.271, 4.300, 4.355), stdev = 0.048
  CI (99.9%): [3.431, 5.169] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.370 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.138 ±(99.9%) 0.003 ms/op
Iteration   1: 4.177 ±(99.9%) 0.003 ms/op
Iteration   2: 4.144 ±(99.9%) 0.002 ms/op
Iteration   3: 3.991 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.104 ±(99.9%) 1.810 ms/op [Average]
  (min, avg, max) = (3.991, 4.104, 4.177), stdev = 0.099
  CI (99.9%): [2.294, 5.914] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.169 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.596 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.004 ms/op
Iteration   1: 4.025 ±(99.9%) 0.002 ms/op
Iteration   2: 4.113 ±(99.9%) 0.004 ms/op
Iteration   3: 4.225 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.121 ±(99.9%) 1.827 ms/op [Average]
  (min, avg, max) = (4.025, 4.121, 4.225), stdev = 0.100
  CI (99.9%): [2.294, 5.948] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.245 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.939 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.247 ±(99.9%) 0.047 ms/op
Iteration   1: 5.047 ±(99.9%) 0.033 ms/op
Iteration   2: 5.075 ±(99.9%) 0.030 ms/op
Iteration   3: 5.437 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.186 ±(99.9%) 3.971 ms/op [Average]
  (min, avg, max) = (5.047, 5.186, 5.437), stdev = 0.218
  CI (99.9%): [1.215, 9.157] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.283 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.395 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.013 ms/op
Iteration   1: 4.279 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   4.149 ms/op
                 createUser·p0.90:   5.503 ms/op
                 createUser·p0.95:   5.882 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  12.550 ms/op
                 createUser·p0.9999: 15.794 ms/op
                 createUser·p1.00:   16.105 ms/op

Iteration   2: 4.304 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   4.174 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   5.915 ms/op
                 createUser·p0.99:   7.186 ms/op
                 createUser·p0.999:  10.568 ms/op
                 createUser·p0.9999: 18.860 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   3: 4.297 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.464 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   7.397 ms/op
                 createUser·p0.999:  13.222 ms/op
                 createUser·p0.9999: 20.203 ms/op
                 createUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 223584
  mean =      4.293 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2544 
    [ 2.500,  5.000) = 173895 
    [ 5.000,  7.500) = 45371 
    [ 7.500, 10.000) = 1258 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      4.174 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     12.138 ms/op
     p(99.9900) =     19.506 ms/op
     p(99.9990) =     20.752 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.017 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.331 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.012 ms/op
Iteration   1: 4.158 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   4.039 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   7.438 ms/op
                 existUser·p0.999:  11.997 ms/op
                 existUser·p0.9999: 17.070 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 3.899 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   5.366 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  11.583 ms/op
                 existUser·p0.9999: 27.997 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   3: 4.190 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   5.718 ms/op
                 existUser·p0.99:   7.881 ms/op
                 existUser·p0.999:  13.780 ms/op
                 existUser·p0.9999: 25.342 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 235199
  mean =      4.078 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5460 
    [ 2.500,  5.000) = 197408 
    [ 5.000,  7.500) = 29997 
    [ 7.500, 10.000) = 1636 
    [10.000, 12.500) = 451 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     12.629 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     28.497 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.468 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.175 ±(99.9%) 0.013 ms/op
Iteration   1: 3.994 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   7.252 ms/op
                 getUser·p0.999:  13.154 ms/op
                 getUser·p0.9999: 17.399 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   2: 4.046 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   5.480 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  14.991 ms/op
                 getUser·p0.9999: 16.915 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   3: 3.886 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  13.987 ms/op
                 getUser·p0.9999: 18.375 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 241429
  mean =      3.974 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 5762 
    [ 2.500,  3.750) = 94145 
    [ 3.750,  5.000) = 122412 
    [ 5.000,  6.250) = 14930 
    [ 6.250,  7.500) = 2243 
    [ 7.500,  8.750) = 686 
    [ 8.750, 10.000) = 339 
    [10.000, 11.250) = 237 
    [11.250, 12.500) = 181 
    [12.500, 13.750) = 148 
    [13.750, 15.000) = 82 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 74 
    [17.500, 18.750) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.806 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.383 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.614 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.332 ±(99.9%) 0.021 ms/op
Iteration   1: 5.439 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   7.365 ms/op
                 listUser·p0.95:   8.159 ms/op
                 listUser·p0.99:   10.633 ms/op
                 listUser·p0.999:  17.140 ms/op
                 listUser·p0.9999: 21.991 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   2: 5.249 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   7.135 ms/op
                 listUser·p0.95:   7.856 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  17.149 ms/op
                 listUser·p0.9999: 27.251 ms/op
                 listUser·p1.00:   29.458 ms/op

Iteration   3: 5.321 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   4.997 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   9.994 ms/op
                 listUser·p0.999:  20.447 ms/op
                 listUser·p0.9999: 24.018 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 179932
  mean =      5.335 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191 
    [ 2.500,  5.000) = 88588 
    [ 5.000,  7.500) = 77011 
    [ 7.500, 10.000) = 12267 
    [10.000, 12.500) = 1275 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      7.225 ms/op
     p(95.0000) =      7.995 ms/op
     p(99.0000) =     10.076 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     23.692 ms/op
     p(99.9990) =     29.327 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.504 ± 1.691  ops/ms
ClientGrpc.existUser                       thrpt       3   7.641 ± 2.106  ops/ms
ClientGrpc.getUser                         thrpt       3   7.497 ± 2.295  ops/ms
ClientGrpc.listUser                        thrpt       3   6.190 ± 0.501  ops/ms
ClientGrpc.createUser                       avgt       3   4.300 ± 0.869   ms/op
ClientGrpc.existUser                        avgt       3   4.104 ± 1.810   ms/op
ClientGrpc.getUser                          avgt       3   4.121 ± 1.827   ms/op
ClientGrpc.listUser                         avgt       3   5.186 ± 3.971   ms/op
ClientGrpc.createUser                     sample  223584   4.293 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.833           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.174           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.497           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.201           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.138           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.506           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.873           ms/op
ClientGrpc.existUser                      sample  235199   4.078 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.931           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.944           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.194           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.595           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.487           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.629           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.804           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.606           ms/op
ClientGrpc.getUser                        sample  241429   3.974 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.636           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.850           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.292           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.021           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.976           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.022           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.907           ms/op
ClientGrpc.listUser                       sample  179932   5.335 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.948           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.995           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.076           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.957           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.692           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.458           ms/op
