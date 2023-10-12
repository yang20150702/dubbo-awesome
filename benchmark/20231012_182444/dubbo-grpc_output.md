# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.183 ops/ms
# Warmup Iteration   2: 6.886 ops/ms
# Warmup Iteration   3: 8.404 ops/ms
Iteration   1: 9.359 ops/ms
Iteration   2: 9.516 ops/ms
Iteration   3: 9.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.516 ±(99.9%) 2.864 ops/ms [Average]
  (min, avg, max) = (9.359, 9.516, 9.673), stdev = 0.157
  CI (99.9%): [6.652, 12.381] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.807 ops/ms
# Warmup Iteration   2: 8.725 ops/ms
# Warmup Iteration   3: 9.129 ops/ms
Iteration   1: 9.663 ops/ms
Iteration   2: 9.737 ops/ms
Iteration   3: 9.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.627 ±(99.9%) 2.427 ops/ms [Average]
  (min, avg, max) = (9.479, 9.627, 9.737), stdev = 0.133
  CI (99.9%): [7.200, 12.053] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.774 ops/ms
# Warmup Iteration   2: 9.160 ops/ms
# Warmup Iteration   3: 9.834 ops/ms
Iteration   1: 9.464 ops/ms
Iteration   2: 9.360 ops/ms
Iteration   3: 9.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.335 ±(99.9%) 2.632 ops/ms [Average]
  (min, avg, max) = (9.179, 9.335, 9.464), stdev = 0.144
  CI (99.9%): [6.703, 11.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.644 ops/ms
# Warmup Iteration   2: 6.555 ops/ms
# Warmup Iteration   3: 6.830 ops/ms
Iteration   1: 7.036 ops/ms
Iteration   2: 7.018 ops/ms
Iteration   3: 7.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.074 ±(99.9%) 1.488 ops/ms [Average]
  (min, avg, max) = (7.018, 7.074, 7.167), stdev = 0.082
  CI (99.9%): [5.586, 8.562] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.546 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.009 ms/op
Iteration   1: 3.404 ±(99.9%) 0.010 ms/op
Iteration   2: 3.505 ±(99.9%) 0.002 ms/op
Iteration   3: 3.647 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.519 ±(99.9%) 2.228 ms/op [Average]
  (min, avg, max) = (3.404, 3.519, 3.647), stdev = 0.122
  CI (99.9%): [1.290, 5.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.553 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.001 ms/op
Iteration   1: 3.355 ±(99.9%) 0.001 ms/op
Iteration   2: 3.150 ±(99.9%) 0.002 ms/op
Iteration   3: 3.175 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.227 ±(99.9%) 2.043 ms/op [Average]
  (min, avg, max) = (3.150, 3.227, 3.355), stdev = 0.112
  CI (99.9%): [1.183, 5.270] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.934 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.517 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.002 ms/op
Iteration   1: 3.321 ±(99.9%) 0.002 ms/op
Iteration   2: 3.539 ±(99.9%) 0.002 ms/op
Iteration   3: 3.662 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.507 ±(99.9%) 3.147 ms/op [Average]
  (min, avg, max) = (3.321, 3.507, 3.662), stdev = 0.172
  CI (99.9%): [0.360, 6.654] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.907 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.410 ±(99.9%) 0.021 ms/op
Iteration   1: 4.543 ±(99.9%) 0.022 ms/op
Iteration   2: 4.658 ±(99.9%) 0.019 ms/op
Iteration   3: 4.524 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.575 ±(99.9%) 1.315 ms/op [Average]
  (min, avg, max) = (4.524, 4.575, 4.658), stdev = 0.072
  CI (99.9%): [3.260, 5.890] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.491 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.009 ms/op
Iteration   1: 3.723 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  14.826 ms/op
                 createUser·p0.9999: 21.845 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   2: 3.788 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  8.979 ms/op
                 createUser·p0.9999: 22.333 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   3: 3.625 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  11.970 ms/op
                 createUser·p0.9999: 26.062 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258576
  mean =      3.711 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1938 
    [ 2.500,  5.000) = 249561 
    [ 5.000,  7.500) = 5963 
    [ 7.500, 10.000) = 743 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     12.583 ms/op
     p(99.9900) =     24.562 ms/op
     p(99.9990) =     26.452 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.812 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.007 ms/op
Iteration   1: 3.505 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  9.603 ms/op
                 existUser·p0.9999: 16.660 ms/op
                 existUser·p1.00:   17.007 ms/op

Iteration   2: 3.355 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  8.618 ms/op
                 existUser·p0.9999: 18.660 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 3.446 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.570 ms/op
                 existUser·p0.999:  13.435 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279389
  mean =      3.434 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10222 
    [ 2.500,  5.000) = 265316 
    [ 5.000,  7.500) = 2906 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.087 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.010 ms/op
Iteration   1: 3.442 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  9.224 ms/op
                 getUser·p0.9999: 22.469 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   2: 3.431 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  11.053 ms/op
                 getUser·p0.9999: 27.197 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   3: 3.466 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  9.981 ms/op
                 getUser·p0.9999: 31.384 ms/op
                 getUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 278661
  mean =      3.446 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10789 
    [ 2.500,  5.000) = 262741 
    [ 5.000,  7.500) = 4346 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     10.306 ms/op
     p(99.9900) =     29.434 ms/op
     p(99.9990) =     31.457 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.307 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.766 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.689 ±(99.9%) 0.013 ms/op
Iteration   1: 4.609 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  16.418 ms/op
                 listUser·p0.9999: 20.257 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   2: 4.399 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.800 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 4.300 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   4.170 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  18.743 ms/op
                 listUser·p0.9999: 21.613 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 216609
  mean =      4.432 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 712 
    [ 2.500,  5.000) = 184213 
    [ 5.000,  7.500) = 28364 
    [ 7.500, 10.000) = 2501 
    [10.000, 12.500) = 353 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      8.061 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     20.786 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.516 ± 2.864  ops/ms
ClientGrpc.existUser                       thrpt       3   9.627 ± 2.427  ops/ms
ClientGrpc.getUser                         thrpt       3   9.335 ± 2.632  ops/ms
ClientGrpc.listUser                        thrpt       3   7.074 ± 1.488  ops/ms
ClientGrpc.createUser                       avgt       3   3.519 ± 2.228   ms/op
ClientGrpc.existUser                        avgt       3   3.227 ± 2.043   ms/op
ClientGrpc.getUser                          avgt       3   3.507 ± 3.147   ms/op
ClientGrpc.listUser                         avgt       3   4.575 ± 1.315   ms/op
ClientGrpc.createUser                     sample  258576   3.711 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.043           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.103           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.583           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.562           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.575           ms/op
ClientGrpc.existUser                      sample  279389   3.434 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.664           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.308           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.764           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.331           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.657           ms/op
ClientGrpc.getUser                        sample  278661   3.446 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.568           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.379           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.125           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.546           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.306           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.434           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.457           ms/op
ClientGrpc.listUser                       sample  216609   4.432 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.807           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.309           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.005           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.061           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.876           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.786           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.200           ms/op
