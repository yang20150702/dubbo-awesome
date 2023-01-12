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
# Warmup Iteration   1: 4.719 ops/ms
# Warmup Iteration   2: 9.160 ops/ms
# Warmup Iteration   3: 10.143 ops/ms
Iteration   1: 10.476 ops/ms
Iteration   2: 10.470 ops/ms
Iteration   3: 10.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.334 ±(99.9%) 4.381 ops/ms [Average]
  (min, avg, max) = (10.057, 10.334, 10.476), stdev = 0.240
  CI (99.9%): [5.953, 14.715] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.967 ops/ms
# Warmup Iteration   2: 10.597 ops/ms
# Warmup Iteration   3: 10.528 ops/ms
Iteration   1: 10.781 ops/ms
Iteration   2: 10.718 ops/ms
Iteration   3: 10.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.703 ±(99.9%) 1.570 ops/ms [Average]
  (min, avg, max) = (10.611, 10.703, 10.781), stdev = 0.086
  CI (99.9%): [9.133, 12.274] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.218 ops/ms
# Warmup Iteration   2: 9.992 ops/ms
# Warmup Iteration   3: 10.083 ops/ms
Iteration   1: 10.176 ops/ms
Iteration   2: 10.775 ops/ms
Iteration   3: 10.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.428 ±(99.9%) 5.672 ops/ms [Average]
  (min, avg, max) = (10.176, 10.428, 10.775), stdev = 0.311
  CI (99.9%): [4.756, 16.100] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.266 ops/ms
# Warmup Iteration   2: 7.599 ops/ms
# Warmup Iteration   3: 7.784 ops/ms
Iteration   1: 8.023 ops/ms
Iteration   2: 7.947 ops/ms
Iteration   3: 8.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.036 ±(99.9%) 1.743 ops/ms [Average]
  (min, avg, max) = (7.947, 8.036, 8.137), stdev = 0.096
  CI (99.9%): [6.293, 9.779] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.002 ms/op
Iteration   1: 3.074 ±(99.9%) 0.002 ms/op
Iteration   2: 3.137 ±(99.9%) 0.002 ms/op
Iteration   3: 3.143 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.118 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (3.074, 3.118, 3.143), stdev = 0.038
  CI (99.9%): [2.421, 3.815] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.792 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.002 ms/op
Iteration   1: 3.007 ±(99.9%) 0.001 ms/op
Iteration   2: 2.957 ±(99.9%) 0.003 ms/op
Iteration   3: 3.015 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.993 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (2.957, 2.993, 3.015), stdev = 0.031
  CI (99.9%): [2.419, 3.567] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.128 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.003 ms/op
Iteration   1: 3.197 ±(99.9%) 0.004 ms/op
Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
Iteration   3: 3.094 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.106 ±(99.9%) 1.563 ms/op [Average]
  (min, avg, max) = (3.027, 3.106, 3.197), stdev = 0.086
  CI (99.9%): [1.543, 4.669] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.369 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.243 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.034 ms/op
Iteration   1: 3.985 ±(99.9%) 0.030 ms/op
Iteration   2: 4.170 ±(99.9%) 0.031 ms/op
Iteration   3: 4.050 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.068 ±(99.9%) 1.716 ms/op [Average]
  (min, avg, max) = (3.985, 4.068, 4.170), stdev = 0.094
  CI (99.9%): [2.352, 5.784] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.248 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.007 ms/op
Iteration   1: 3.125 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  6.763 ms/op
                 createUser·p0.9999: 14.676 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  9.087 ms/op
                 createUser·p0.9999: 17.392 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   3: 3.217 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  8.585 ms/op
                 createUser·p0.9999: 21.860 ms/op
                 createUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303029
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19135 
    [ 2.500,  5.000) = 282644 
    [ 5.000,  7.500) = 783 
    [ 7.500, 10.000) = 243 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     22.281 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.885 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
Iteration   1: 2.945 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.783 ms/op
                 existUser·p0.9999: 13.097 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  6.273 ms/op
                 existUser·p0.9999: 14.344 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  10.469 ms/op
                 existUser·p0.9999: 19.396 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319325
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37872 
    [ 2.500,  5.000) = 280522 
    [ 5.000,  7.500) = 563 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.106 ms/op
     p(99.9900) =     18.029 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.841 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 3.104 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.979 ms/op
                 getUser·p0.9999: 11.857 ms/op
                 getUser·p1.00:   12.141 ms/op

Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  7.287 ms/op
                 getUser·p0.9999: 26.290 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   3: 3.200 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.529 ms/op
                 getUser·p0.9999: 16.302 ms/op
                 getUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306597
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19133 
    [ 2.500,  5.000) = 286613 
    [ 5.000,  7.500) = 568 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.278 ms/op
     p(99.9900) =     25.171 ms/op
     p(99.9990) =     26.540 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.301 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.012 ms/op
Iteration   1: 4.056 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.033 ms/op
                 listUser·p0.999:  16.403 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   2: 4.011 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.032 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  16.037 ms/op
                 listUser·p0.9999: 23.922 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   3: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.977 ms/op
                 listUser·p0.9999: 24.502 ms/op
                 listUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239444
  mean =      4.007 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2683 
    [ 2.500,  5.000) = 211352 
    [ 5.000,  7.500) = 24055 
    [ 7.500, 10.000) = 853 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     23.857 ms/op
     p(99.9990) =     24.892 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.334 ± 4.381  ops/ms
ClientGrpc.existUser                       thrpt       3  10.703 ± 1.570  ops/ms
ClientGrpc.getUser                         thrpt       3  10.428 ± 5.672  ops/ms
ClientGrpc.listUser                        thrpt       3   8.036 ± 1.743  ops/ms
ClientGrpc.createUser                       avgt       3   3.118 ± 0.697   ms/op
ClientGrpc.existUser                        avgt       3   2.993 ± 0.574   ms/op
ClientGrpc.getUser                          avgt       3   3.106 ± 1.563   ms/op
ClientGrpc.listUser                         avgt       3   4.068 ± 1.716   ms/op
ClientGrpc.createUser                     sample  303029   3.167 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.552           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.030           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.585           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.283           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.413           ms/op
ClientGrpc.existUser                      sample  319325   3.006 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.663           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.106           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.029           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.677           ms/op
ClientGrpc.getUser                        sample  306597   3.132 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.602           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.936           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.278           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.171           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.608           ms/op
ClientGrpc.listUser                       sample  239444   4.007 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.032           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.857           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.035           ms/op
