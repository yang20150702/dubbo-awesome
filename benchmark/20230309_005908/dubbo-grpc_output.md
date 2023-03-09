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
# Warmup Iteration   1: 4.103 ops/ms
# Warmup Iteration   2: 8.682 ops/ms
# Warmup Iteration   3: 10.061 ops/ms
Iteration   1: 10.341 ops/ms
Iteration   2: 10.267 ops/ms
Iteration   3: 10.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.294 ±(99.9%) 0.743 ops/ms [Average]
  (min, avg, max) = (10.267, 10.294, 10.341), stdev = 0.041
  CI (99.9%): [9.551, 11.038] (assumes normal distribution)


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
# Warmup Iteration   1: 6.883 ops/ms
# Warmup Iteration   2: 9.666 ops/ms
# Warmup Iteration   3: 10.267 ops/ms
Iteration   1: 10.256 ops/ms
Iteration   2: 10.522 ops/ms
Iteration   3: 10.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.347 ±(99.9%) 2.760 ops/ms [Average]
  (min, avg, max) = (10.256, 10.347, 10.522), stdev = 0.151
  CI (99.9%): [7.587, 13.107] (assumes normal distribution)


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
# Warmup Iteration   1: 7.312 ops/ms
# Warmup Iteration   2: 9.512 ops/ms
# Warmup Iteration   3: 9.640 ops/ms
Iteration   1: 9.647 ops/ms
Iteration   2: 9.948 ops/ms
Iteration   3: 9.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.814 ±(99.9%) 2.795 ops/ms [Average]
  (min, avg, max) = (9.647, 9.814, 9.948), stdev = 0.153
  CI (99.9%): [7.019, 12.609] (assumes normal distribution)


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
# Warmup Iteration   1: 5.350 ops/ms
# Warmup Iteration   2: 6.853 ops/ms
# Warmup Iteration   3: 7.278 ops/ms
Iteration   1: 7.250 ops/ms
Iteration   2: 7.308 ops/ms
Iteration   3: 7.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.292 ±(99.9%) 0.672 ops/ms [Average]
  (min, avg, max) = (7.250, 7.292, 7.319), stdev = 0.037
  CI (99.9%): [6.620, 7.964] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.463 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.002 ms/op
Iteration   1: 3.288 ±(99.9%) 0.002 ms/op
Iteration   2: 3.273 ±(99.9%) 0.003 ms/op
Iteration   3: 3.331 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.297 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (3.273, 3.297, 3.331), stdev = 0.031
  CI (99.9%): [2.741, 3.854] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.316 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.003 ms/op
Iteration   1: 3.101 ±(99.9%) 0.003 ms/op
Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
Iteration   3: 3.112 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.116 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.101, 3.116, 3.135), stdev = 0.018
  CI (99.9%): [2.794, 3.439] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.407 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.002 ms/op
Iteration   1: 3.270 ±(99.9%) 0.002 ms/op
Iteration   2: 3.254 ±(99.9%) 0.003 ms/op
Iteration   3: 3.313 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.279 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (3.254, 3.279, 3.313), stdev = 0.030
  CI (99.9%): [2.728, 3.830] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.133 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.531 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.286 ±(99.9%) 0.014 ms/op
Iteration   1: 4.320 ±(99.9%) 0.012 ms/op
Iteration   2: 4.305 ±(99.9%) 0.019 ms/op
Iteration   3: 4.284 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.303 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (4.284, 4.303, 4.320), stdev = 0.018
  CI (99.9%): [3.970, 4.636] (assumes normal distribution)


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
# Warmup Iteration   1: 4.828 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.006 ms/op
Iteration   1: 3.266 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  6.923 ms/op
                 createUser·p0.9999: 13.012 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   2: 3.267 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.504 ms/op
                 createUser·p0.9999: 15.001 ms/op
                 createUser·p1.00:   15.368 ms/op

Iteration   3: 3.242 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 18.559 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294676
  mean =      3.258 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 708 
    [ 1.250,  2.500) = 10837 
    [ 2.500,  3.750) = 256328 
    [ 3.750,  5.000) = 25453 
    [ 5.000,  6.250) = 704 
    [ 6.250,  7.500) = 337 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.673 ms/op
     p(99.9900) =     17.024 ms/op
     p(99.9990) =     18.845 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 3.908 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.005 ms/op
Iteration   1: 3.170 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  7.274 ms/op
                 existUser·p0.9999: 12.237 ms/op
                 existUser·p1.00:   13.222 ms/op

Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  7.503 ms/op
                 existUser·p0.9999: 15.378 ms/op
                 existUser·p1.00:   15.811 ms/op

Iteration   3: 3.157 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.682 ms/op
                 existUser·p0.9999: 17.152 ms/op
                 existUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 303603
  mean =      3.161 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1433 
    [ 1.250,  2.500) = 13760 
    [ 2.500,  3.750) = 268065 
    [ 3.750,  5.000) = 19125 
    [ 5.000,  6.250) = 721 
    [ 6.250,  7.500) = 266 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.086 ms/op
     p(99.9900) =     15.952 ms/op
     p(99.9990) =     17.431 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 5.211 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.007 ms/op
Iteration   1: 3.258 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  9.631 ms/op
                 getUser·p0.9999: 13.840 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 3.259 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.611 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  7.101 ms/op
                 getUser·p0.9999: 16.783 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   3: 3.238 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  9.360 ms/op
                 getUser·p0.9999: 21.930 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 294967
  mean =      3.252 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16030 
    [ 2.500,  5.000) = 277315 
    [ 5.000,  7.500) = 1256 
    [ 7.500, 10.000) = 172 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     19.939 ms/op
     p(99.9990) =     22.318 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 5.757 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.369 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.345 ±(99.9%) 0.013 ms/op
Iteration   1: 4.351 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   4.166 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  16.221 ms/op
                 listUser·p0.9999: 21.823 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 4.263 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   3: 4.247 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  16.417 ms/op
                 listUser·p0.9999: 20.790 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 223930
  mean =      4.286 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1825 
    [ 2.500,  5.000) = 192905 
    [ 5.000,  7.500) = 26813 
    [ 7.500, 10.000) = 1908 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      4.121 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      6.250 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     23.201 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.294 ± 0.743  ops/ms
ClientGrpc.existUser                       thrpt       3  10.347 ± 2.760  ops/ms
ClientGrpc.getUser                         thrpt       3   9.814 ± 2.795  ops/ms
ClientGrpc.listUser                        thrpt       3   7.292 ± 0.672  ops/ms
ClientGrpc.createUser                       avgt       3   3.297 ± 0.557   ms/op
ClientGrpc.existUser                        avgt       3   3.116 ± 0.322   ms/op
ClientGrpc.getUser                          avgt       3   3.279 ± 0.551   ms/op
ClientGrpc.listUser                         avgt       3   4.303 ± 0.333   ms/op
ClientGrpc.createUser                     sample  294676   3.258 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.256           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.673           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.024           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.973           ms/op
ClientGrpc.existUser                      sample  303603   3.161 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.728           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.170           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.086           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.952           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.662           ms/op
ClientGrpc.getUser                        sample  294967   3.252 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.611           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.265           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.661           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.651           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.939           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.446           ms/op
ClientGrpc.listUser                       sample  223930   4.286 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.879           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.121           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.250           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.561           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.811           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.201           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.314           ms/op
