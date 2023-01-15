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
# Warmup Iteration   1: 3.209 ops/ms
# Warmup Iteration   2: 7.065 ops/ms
# Warmup Iteration   3: 8.466 ops/ms
Iteration   1: 8.752 ops/ms
Iteration   2: 8.615 ops/ms
Iteration   3: 8.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.692 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (8.615, 8.692, 8.752), stdev = 0.070
  CI (99.9%): [7.418, 9.965] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.071 ops/ms
# Warmup Iteration   2: 8.827 ops/ms
# Warmup Iteration   3: 9.213 ops/ms
Iteration   1: 9.471 ops/ms
Iteration   2: 9.149 ops/ms
Iteration   3: 9.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.229 ±(99.9%) 3.896 ops/ms [Average]
  (min, avg, max) = (9.066, 9.229, 9.471), stdev = 0.214
  CI (99.9%): [5.333, 13.124] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.938 ops/ms
# Warmup Iteration   2: 8.382 ops/ms
# Warmup Iteration   3: 9.039 ops/ms
Iteration   1: 8.856 ops/ms
Iteration   2: 8.811 ops/ms
Iteration   3: 8.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.703 ±(99.9%) 4.131 ops/ms [Average]
  (min, avg, max) = (8.443, 8.703, 8.856), stdev = 0.226
  CI (99.9%): [4.572, 12.834] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.704 ops/ms
# Warmup Iteration   2: 6.295 ops/ms
# Warmup Iteration   3: 6.805 ops/ms
Iteration   1: 6.868 ops/ms
Iteration   2: 6.692 ops/ms
Iteration   3: 6.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.780 ±(99.9%) 1.605 ops/ms [Average]
  (min, avg, max) = (6.692, 6.780, 6.868), stdev = 0.088
  CI (99.9%): [5.175, 8.385] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.393 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.004 ms/op
Iteration   1: 3.602 ±(99.9%) 0.004 ms/op
Iteration   2: 3.560 ±(99.9%) 0.004 ms/op
Iteration   3: 3.571 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.578 ±(99.9%) 0.392 ms/op [Average]
  (min, avg, max) = (3.560, 3.578, 3.602), stdev = 0.021
  CI (99.9%): [3.186, 3.969] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.652 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.003 ms/op
Iteration   1: 3.384 ±(99.9%) 0.004 ms/op
Iteration   2: 3.291 ±(99.9%) 0.007 ms/op
Iteration   3: 3.302 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.326 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (3.291, 3.326, 3.384), stdev = 0.051
  CI (99.9%): [2.396, 4.255] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.691 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.003 ms/op
Iteration   1: 3.620 ±(99.9%) 0.003 ms/op
Iteration   2: 3.532 ±(99.9%) 0.002 ms/op
Iteration   3: 3.673 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.608 ±(99.9%) 1.298 ms/op [Average]
  (min, avg, max) = (3.532, 3.608, 3.673), stdev = 0.071
  CI (99.9%): [2.310, 4.907] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.515 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.674 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.640 ±(99.9%) 0.021 ms/op
Iteration   1: 4.517 ±(99.9%) 0.009 ms/op
Iteration   2: 4.454 ±(99.9%) 0.008 ms/op
Iteration   3: 4.633 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.535 ±(99.9%) 1.653 ms/op [Average]
  (min, avg, max) = (4.454, 4.535, 4.633), stdev = 0.091
  CI (99.9%): [2.882, 6.188] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.032 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.009 ms/op
Iteration   1: 3.526 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  13.671 ms/op
                 createUser·p0.9999: 19.399 ms/op
                 createUser·p1.00:   19.759 ms/op

Iteration   2: 3.621 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  8.782 ms/op
                 createUser·p0.9999: 24.352 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.562 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  9.586 ms/op
                 createUser·p0.9999: 22.872 ms/op
                 createUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 269119
  mean =      3.569 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12012 
    [ 2.500,  5.000) = 251124 
    [ 5.000,  7.500) = 5156 
    [ 7.500, 10.000) = 544 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     10.973 ms/op
     p(99.9900) =     22.949 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.783 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.008 ms/op
Iteration   1: 3.441 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  11.301 ms/op
                 existUser·p0.9999: 16.898 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   2: 3.448 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  8.703 ms/op
                 existUser·p0.9999: 19.071 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   3: 3.476 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  12.758 ms/op
                 existUser·p0.9999: 26.044 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 278082
  mean =      3.455 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14441 
    [ 2.500,  5.000) = 258785 
    [ 5.000,  7.500) = 4016 
    [ 7.500, 10.000) = 598 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     26.236 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 4.971 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.009 ms/op
Iteration   1: 3.729 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  9.015 ms/op
                 getUser·p0.9999: 16.363 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   2: 3.582 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  10.462 ms/op
                 getUser·p0.9999: 24.414 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   3: 3.569 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  7.764 ms/op
                 getUser·p0.9999: 19.073 ms/op
                 getUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 264763
  mean =      3.625 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9326 
    [ 2.500,  5.000) = 248702 
    [ 5.000,  7.500) = 6101 
    [ 7.500, 10.000) = 444 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      8.871 ms/op
     p(99.9900) =     22.892 ms/op
     p(99.9990) =     25.004 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 5.960 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.872 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.617 ±(99.9%) 0.013 ms/op
Iteration   1: 4.692 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.997 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  14.195 ms/op
                 listUser·p0.9999: 19.476 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   2: 4.652 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.915 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  16.324 ms/op
                 listUser·p0.9999: 25.801 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   3: 4.716 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   6.046 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  19.530 ms/op
                 listUser·p0.9999: 21.208 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204737
  mean =      4.686 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 503 
    [ 2.500,  5.000) = 153791 
    [ 5.000,  7.500) = 46196 
    [ 7.500, 10.000) = 3540 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.644 ms/op
     p(99.0000) =      8.233 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     25.314 ms/op
     p(99.9990) =     26.175 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.692 ± 1.273  ops/ms
ClientGrpc.existUser                       thrpt       3   9.229 ± 3.896  ops/ms
ClientGrpc.getUser                         thrpt       3   8.703 ± 4.131  ops/ms
ClientGrpc.listUser                        thrpt       3   6.780 ± 1.605  ops/ms
ClientGrpc.createUser                       avgt       3   3.578 ± 0.392   ms/op
ClientGrpc.existUser                        avgt       3   3.326 ± 0.930   ms/op
ClientGrpc.getUser                          avgt       3   3.608 ± 1.298   ms/op
ClientGrpc.listUser                         avgt       3   4.535 ± 1.653   ms/op
ClientGrpc.createUser                     sample  269119   3.569 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.674           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.669           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.973           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.949           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.576           ms/op
ClientGrpc.existUser                      sample  278082   3.455 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.689           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.191           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.756           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.279           ms/op
ClientGrpc.getUser                        sample  264763   3.625 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.635           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.636           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.871           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.892           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.199           ms/op
ClientGrpc.listUser                       sample  204737   4.686 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.122           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.481           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.233           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.022           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.314           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.313           ms/op
