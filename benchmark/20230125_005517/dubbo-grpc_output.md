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
# Warmup Iteration   1: 4.903 ops/ms
# Warmup Iteration   2: 9.729 ops/ms
# Warmup Iteration   3: 10.442 ops/ms
Iteration   1: 10.745 ops/ms
Iteration   2: 10.264 ops/ms
Iteration   3: 10.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.526 ±(99.9%) 4.442 ops/ms [Average]
  (min, avg, max) = (10.264, 10.526, 10.745), stdev = 0.243
  CI (99.9%): [6.084, 14.967] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.161 ops/ms
# Warmup Iteration   2: 10.641 ops/ms
# Warmup Iteration   3: 10.874 ops/ms
Iteration   1: 11.040 ops/ms
Iteration   2: 10.742 ops/ms
Iteration   3: 10.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.909 ±(99.9%) 2.783 ops/ms [Average]
  (min, avg, max) = (10.742, 10.909, 11.040), stdev = 0.153
  CI (99.9%): [8.126, 13.693] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.583 ops/ms
# Warmup Iteration   2: 10.145 ops/ms
# Warmup Iteration   3: 10.469 ops/ms
Iteration   1: 10.302 ops/ms
Iteration   2: 10.744 ops/ms
Iteration   3: 10.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.556 ±(99.9%) 4.164 ops/ms [Average]
  (min, avg, max) = (10.302, 10.556, 10.744), stdev = 0.228
  CI (99.9%): [6.392, 14.720] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.760 ops/ms
# Warmup Iteration   2: 7.686 ops/ms
# Warmup Iteration   3: 7.778 ops/ms
Iteration   1: 7.974 ops/ms
Iteration   2: 8.204 ops/ms
Iteration   3: 7.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.014 ±(99.9%) 3.168 ops/ms [Average]
  (min, avg, max) = (7.864, 8.014, 8.204), stdev = 0.174
  CI (99.9%): [4.846, 11.182] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.897 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.004 ms/op
Iteration   1: 3.224 ±(99.9%) 0.002 ms/op
Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
Iteration   3: 3.191 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.166 ±(99.9%) 1.355 ms/op [Average]
  (min, avg, max) = (3.082, 3.166, 3.224), stdev = 0.074
  CI (99.9%): [1.811, 4.521] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.005 ms/op
Iteration   1: 3.200 ±(99.9%) 0.002 ms/op
Iteration   2: 3.083 ±(99.9%) 0.003 ms/op
Iteration   3: 2.958 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.080 ±(99.9%) 2.208 ms/op [Average]
  (min, avg, max) = (2.958, 3.080, 3.200), stdev = 0.121
  CI (99.9%): [0.872, 5.289] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.089 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.002 ms/op
Iteration   1: 3.034 ±(99.9%) 0.003 ms/op
Iteration   2: 3.091 ±(99.9%) 0.004 ms/op
Iteration   3: 2.928 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.018 ±(99.9%) 1.507 ms/op [Average]
  (min, avg, max) = (2.928, 3.018, 3.091), stdev = 0.083
  CI (99.9%): [1.511, 4.525] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.226 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.048 ms/op
Iteration   1: 4.027 ±(99.9%) 0.010 ms/op
Iteration   2: 4.076 ±(99.9%) 0.021 ms/op
Iteration   3: 4.167 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.090 ±(99.9%) 1.293 ms/op [Average]
  (min, avg, max) = (4.027, 4.090, 4.167), stdev = 0.071
  CI (99.9%): [2.797, 5.383] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.033 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
Iteration   1: 3.207 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.623 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  6.423 ms/op
                 createUser·p0.9999: 11.534 ms/op
                 createUser·p1.00:   11.862 ms/op

Iteration   2: 3.056 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.765 ms/op
                 createUser·p0.9999: 14.000 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   3: 3.151 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.541 ms/op
                 createUser·p0.999:  10.773 ms/op
                 createUser·p0.9999: 23.387 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305970
  mean =      3.137 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21689 
    [ 2.500,  5.000) = 282928 
    [ 5.000,  7.500) = 992 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     23.786 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.891 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
Iteration   1: 3.056 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  6.409 ms/op
                 existUser·p0.9999: 14.214 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 3.060 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.717 ms/op
                 existUser·p0.9999: 23.691 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  7.306 ms/op
                 existUser·p0.9999: 14.915 ms/op
                 existUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315534
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39698 
    [ 2.500,  5.000) = 274664 
    [ 5.000,  7.500) = 928 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.094 ms/op
     p(99.9900) =     22.406 ms/op
     p(99.9990) =     25.751 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.007 ms/op
Iteration   1: 3.014 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.183 ms/op
                 getUser·p0.9999: 15.600 ms/op
                 getUser·p1.00:   15.958 ms/op

Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  7.196 ms/op
                 getUser·p0.9999: 12.960 ms/op
                 getUser·p1.00:   13.287 ms/op

Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.383 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.340 ms/op
                 getUser·p0.9999: 27.329 ms/op
                 getUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313409
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33066 
    [ 2.500,  5.000) = 278782 
    [ 5.000,  7.500) = 1294 
    [ 7.500, 10.000) = 139 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.234 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     27.750 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.011 ms/op
Iteration   1: 4.021 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  12.328 ms/op
                 listUser·p0.9999: 18.156 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   2: 3.948 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 30.763 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   3: 3.999 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.722 ms/op
                 listUser·p0.999:  14.694 ms/op
                 listUser·p0.9999: 22.544 ms/op
                 listUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240681
  mean =      3.989 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4091 
    [ 2.500,  5.000) = 209549 
    [ 5.000,  7.500) = 25869 
    [ 7.500, 10.000) = 711 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     14.510 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     33.343 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.526 ± 4.442  ops/ms
ClientGrpc.existUser                       thrpt       3  10.909 ± 2.783  ops/ms
ClientGrpc.getUser                         thrpt       3  10.556 ± 4.164  ops/ms
ClientGrpc.listUser                        thrpt       3   8.014 ± 3.168  ops/ms
ClientGrpc.createUser                       avgt       3   3.166 ± 1.355   ms/op
ClientGrpc.existUser                        avgt       3   3.080 ± 2.208   ms/op
ClientGrpc.getUser                          avgt       3   3.018 ± 1.507   ms/op
ClientGrpc.listUser                         avgt       3   4.090 ± 1.293   ms/op
ClientGrpc.createUser                     sample  305970   3.137 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.522           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.765           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.234           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.953           ms/op
ClientGrpc.existUser                      sample  315534   3.040 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.654           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.924           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.094           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.406           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.952           ms/op
ClientGrpc.getUser                        sample  313409   3.062 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.383           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.234           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.673           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.115           ms/op
ClientGrpc.listUser                       sample  240681   3.989 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.845           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.510           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.296           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.620           ms/op
