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
# Warmup Iteration   1: 4.602 ops/ms
# Warmup Iteration   2: 9.249 ops/ms
# Warmup Iteration   3: 10.161 ops/ms
Iteration   1: 10.687 ops/ms
Iteration   2: 10.889 ops/ms
Iteration   3: 10.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.831 ±(99.9%) 2.292 ops/ms [Average]
  (min, avg, max) = (10.687, 10.831, 10.918), stdev = 0.126
  CI (99.9%): [8.539, 13.124] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.058 ops/ms
# Warmup Iteration   2: 10.826 ops/ms
# Warmup Iteration   3: 11.734 ops/ms
Iteration   1: 11.224 ops/ms
Iteration   2: 11.349 ops/ms
Iteration   3: 11.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.413 ±(99.9%) 4.158 ops/ms [Average]
  (min, avg, max) = (11.224, 11.413, 11.666), stdev = 0.228
  CI (99.9%): [7.255, 15.571] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.197 ops/ms
# Warmup Iteration   2: 10.306 ops/ms
# Warmup Iteration   3: 10.794 ops/ms
Iteration   1: 10.624 ops/ms
Iteration   2: 10.711 ops/ms
Iteration   3: 10.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.707 ±(99.9%) 1.478 ops/ms [Average]
  (min, avg, max) = (10.624, 10.707, 10.786), stdev = 0.081
  CI (99.9%): [9.229, 12.185] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.272 ops/ms
# Warmup Iteration   2: 7.849 ops/ms
# Warmup Iteration   3: 8.004 ops/ms
Iteration   1: 8.241 ops/ms
Iteration   2: 8.328 ops/ms
Iteration   3: 8.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.247 ±(99.9%) 1.440 ops/ms [Average]
  (min, avg, max) = (8.171, 8.247, 8.328), stdev = 0.079
  CI (99.9%): [6.807, 9.687] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.009 ms/op
Iteration   1: 2.970 ±(99.9%) 0.002 ms/op
Iteration   2: 3.076 ±(99.9%) 0.002 ms/op
Iteration   3: 2.990 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.012 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (2.970, 3.012, 3.076), stdev = 0.056
  CI (99.9%): [1.987, 4.037] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.862 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.889 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.841 ±(99.9%) 0.004 ms/op
Iteration   1: 2.872 ±(99.9%) 0.003 ms/op
Iteration   2: 2.821 ±(99.9%) 0.004 ms/op
Iteration   3: 2.852 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.848 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (2.821, 2.848, 2.872), stdev = 0.026
  CI (99.9%): [2.372, 3.324] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.793 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.003 ms/op
Iteration   2: 2.956 ±(99.9%) 0.003 ms/op
Iteration   3: 2.956 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.961 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (2.956, 2.961, 2.971), stdev = 0.009
  CI (99.9%): [2.804, 3.118] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.084 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.025 ms/op
Iteration   1: 3.919 ±(99.9%) 0.012 ms/op
Iteration   2: 3.821 ±(99.9%) 0.011 ms/op
Iteration   3: 3.928 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.889 ±(99.9%) 1.087 ms/op [Average]
  (min, avg, max) = (3.821, 3.889, 3.928), stdev = 0.060
  CI (99.9%): [2.802, 4.977] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.613 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  7.237 ms/op
                 createUser·p0.9999: 16.192 ms/op
                 createUser·p1.00:   16.679 ms/op

Iteration   2: 2.982 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.261 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  13.963 ms/op
                 createUser·p0.9999: 21.013 ms/op
                 createUser·p1.00:   21.365 ms/op

Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.712 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.494 ms/op
                 createUser·p0.9999: 21.594 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317778
  mean =      3.021 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29271 
    [ 2.500,  5.000) = 286501 
    [ 5.000,  7.500) = 1515 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.261 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      9.293 ms/op
     p(99.9900) =     21.143 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.909 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.844 ±(99.9%) 0.006 ms/op
Iteration   1: 2.853 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.313 ms/op
                 existUser·p0.9999: 15.656 ms/op
                 existUser·p1.00:   16.597 ms/op

Iteration   2: 2.835 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.205 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  8.636 ms/op
                 existUser·p0.9999: 20.349 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   3: 2.891 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.524 ms/op
                 existUser·p0.999:  10.391 ms/op
                 existUser·p0.9999: 18.022 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335971
  mean =      2.859 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54611 
    [ 2.500,  5.000) = 279519 
    [ 5.000,  7.500) = 1333 
    [ 7.500, 10.000) = 242 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.205 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.034 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.925 ms/op
                 getUser·p0.9999: 10.348 ms/op
                 getUser·p1.00:   10.977 ms/op

Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.791 ms/op
                 getUser·p0.9999: 19.399 ms/op
                 getUser·p1.00:   19.661 ms/op

Iteration   3: 2.980 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  8.239 ms/op
                 getUser·p0.9999: 26.575 ms/op
                 getUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320756
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28277 
    [ 2.500,  5.000) = 290843 
    [ 5.000,  7.500) = 1149 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.995 ms/op
     p(99.9900) =     25.415 ms/op
     p(99.9990) =     26.797 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 5.226 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.010 ms/op
Iteration   1: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  13.908 ms/op
                 listUser·p0.9999: 18.867 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   2: 3.913 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.456 ms/op
                 listUser·p0.9999: 18.545 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   3: 3.861 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.284 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 21.150 ms/op
                 listUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245703
  mean =      3.905 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4702 
    [ 2.500,  5.000) = 221950 
    [ 5.000,  7.500) = 17547 
    [ 7.500, 10.000) = 1020 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.284 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     13.882 ms/op
     p(99.9900) =     20.560 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.831 ± 2.292  ops/ms
ClientGrpc.existUser                       thrpt       3  11.413 ± 4.158  ops/ms
ClientGrpc.getUser                         thrpt       3  10.707 ± 1.478  ops/ms
ClientGrpc.listUser                        thrpt       3   8.247 ± 1.440  ops/ms
ClientGrpc.createUser                       avgt       3   3.012 ± 1.025   ms/op
ClientGrpc.existUser                        avgt       3   2.848 ± 0.476   ms/op
ClientGrpc.getUser                          avgt       3   2.961 ± 0.157   ms/op
ClientGrpc.listUser                         avgt       3   3.889 ± 1.087   ms/op
ClientGrpc.createUser                     sample  317778   3.021 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.261           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.293           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.143           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.020           ms/op
ClientGrpc.existUser                      sample  335971   2.859 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.205           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.815           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.759           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.643           ms/op
ClientGrpc.getUser                        sample  320756   2.992 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.584           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.995           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.415           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.870           ms/op
ClientGrpc.listUser                       sample  245703   3.905 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.284           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.882           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.560           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.282           ms/op
