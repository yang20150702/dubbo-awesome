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
# Warmup Iteration   1: 4.181 ops/ms
# Warmup Iteration   2: 9.343 ops/ms
# Warmup Iteration   3: 9.738 ops/ms
Iteration   1: 10.388 ops/ms
Iteration   2: 10.865 ops/ms
Iteration   3: 10.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.694 ±(99.9%) 4.834 ops/ms [Average]
  (min, avg, max) = (10.388, 10.694, 10.865), stdev = 0.265
  CI (99.9%): [5.859, 15.528] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.549 ops/ms
# Warmup Iteration   2: 10.307 ops/ms
# Warmup Iteration   3: 11.167 ops/ms
Iteration   1: 11.462 ops/ms
Iteration   2: 10.480 ops/ms
Iteration   3: 10.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.707 ±(99.9%) 12.257 ops/ms [Average]
  (min, avg, max) = (10.177, 10.707, 11.462), stdev = 0.672
  CI (99.9%): [≈ 0, 22.964] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.055 ops/ms
# Warmup Iteration   2: 9.434 ops/ms
# Warmup Iteration   3: 10.313 ops/ms
Iteration   1: 10.722 ops/ms
Iteration   2: 10.561 ops/ms
Iteration   3: 10.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.752 ±(99.9%) 3.774 ops/ms [Average]
  (min, avg, max) = (10.561, 10.752, 10.972), stdev = 0.207
  CI (99.9%): [6.978, 14.526] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.530 ops/ms
# Warmup Iteration   2: 7.312 ops/ms
# Warmup Iteration   3: 8.143 ops/ms
Iteration   1: 8.272 ops/ms
Iteration   2: 8.094 ops/ms
Iteration   3: 8.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.161 ±(99.9%) 1.772 ops/ms [Average]
  (min, avg, max) = (8.094, 8.161, 8.272), stdev = 0.097
  CI (99.9%): [6.388, 9.933] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.223 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.005 ms/op
Iteration   1: 3.084 ±(99.9%) 0.003 ms/op
Iteration   2: 2.940 ±(99.9%) 0.002 ms/op
Iteration   3: 3.052 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.026 ±(99.9%) 1.376 ms/op [Average]
  (min, avg, max) = (2.940, 3.026, 3.084), stdev = 0.075
  CI (99.9%): [1.650, 4.401] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.485 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.343 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.003 ms/op
Iteration   1: 3.050 ±(99.9%) 0.002 ms/op
Iteration   2: 2.811 ±(99.9%) 0.003 ms/op
Iteration   3: 2.881 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.914 ±(99.9%) 2.239 ms/op [Average]
  (min, avg, max) = (2.811, 2.914, 3.050), stdev = 0.123
  CI (99.9%): [0.676, 5.153] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.004 ms/op
Iteration   1: 2.976 ±(99.9%) 0.002 ms/op
Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
Iteration   3: 3.015 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.001 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (2.976, 3.001, 3.015), stdev = 0.021
  CI (99.9%): [2.613, 3.388] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.179 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.015 ms/op
Iteration   1: 3.858 ±(99.9%) 0.028 ms/op
Iteration   2: 3.874 ±(99.9%) 0.024 ms/op
Iteration   3: 3.964 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.899 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (3.858, 3.899, 3.964), stdev = 0.057
  CI (99.9%): [2.860, 4.938] (assumes normal distribution)


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
# Warmup Iteration   1: 4.291 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.007 ms/op
Iteration   1: 3.266 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  9.226 ms/op
                 createUser·p0.9999: 14.356 ms/op
                 createUser·p1.00:   14.631 ms/op

Iteration   2: 3.242 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  13.140 ms/op
                 createUser·p0.9999: 18.977 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 3.354 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   4.948 ms/op
                 createUser·p0.999:  9.393 ms/op
                 createUser·p0.9999: 18.186 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 291921
  mean =      3.287 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17787 
    [ 2.500,  5.000) = 270850 
    [ 5.000,  7.500) = 2628 
    [ 7.500, 10.000) = 390 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.118 ms/op
     p(99.9000) =      9.635 ms/op
     p(99.9900) =     18.508 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 4.011 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.957 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.006 ms/op
Iteration   1: 2.842 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   2.806 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  8.110 ms/op
                 existUser·p0.9999: 13.979 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.832 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.496 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.273 ms/op
                 existUser·p0.999:  7.481 ms/op
                 existUser·p0.9999: 17.662 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   3: 2.891 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  11.076 ms/op
                 existUser·p0.9999: 29.423 ms/op
                 existUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336152
  mean =      2.855 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76186 
    [ 2.500,  5.000) = 257887 
    [ 5.000,  7.500) = 1527 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.894 ms/op
     p(99.9900) =     18.932 ms/op
     p(99.9990) =     29.643 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.007 ms/op
Iteration   1: 3.331 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  8.093 ms/op
                 getUser·p0.9999: 16.200 ms/op
                 getUser·p1.00:   16.499 ms/op

Iteration   2: 3.315 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.136 ms/op
                 getUser·p0.999:  10.602 ms/op
                 getUser·p0.9999: 20.939 ms/op
                 getUser·p1.00:   21.070 ms/op

Iteration   3: 3.217 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  9.322 ms/op
                 getUser·p0.9999: 31.523 ms/op
                 getUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 292062
  mean =      3.287 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15559 
    [ 2.500,  5.000) = 273196 
    [ 5.000,  7.500) = 2695 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.098 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     30.756 ms/op
     p(99.9990) =     31.755 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


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
# Warmup Iteration   1: 5.631 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.012 ms/op
Iteration   1: 4.258 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.436 ms/op
                 listUser·p0.50:   4.121 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  14.561 ms/op
                 listUser·p0.9999: 21.396 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 4.299 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.382 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  19.005 ms/op
                 listUser·p0.9999: 26.721 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   3: 4.298 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   4.145 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  19.595 ms/op
                 listUser·p0.9999: 24.758 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 224129
  mean =      4.285 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1779 
    [ 2.500,  5.000) = 194015 
    [ 5.000,  7.500) = 25585 
    [ 7.500, 10.000) = 2141 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     18.342 ms/op
     p(99.9900) =     25.840 ms/op
     p(99.9990) =     27.517 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score    Error   Units
ClientGrpc.createUser                      thrpt       3  10.694 ±  4.834  ops/ms
ClientGrpc.existUser                       thrpt       3  10.707 ± 12.257  ops/ms
ClientGrpc.getUser                         thrpt       3  10.752 ±  3.774  ops/ms
ClientGrpc.listUser                        thrpt       3   8.161 ±  1.772  ops/ms
ClientGrpc.createUser                       avgt       3   3.026 ±  1.376   ms/op
ClientGrpc.existUser                        avgt       3   2.914 ±  2.239   ms/op
ClientGrpc.getUser                          avgt       3   3.001 ±  0.388   ms/op
ClientGrpc.listUser                         avgt       3   3.899 ±  1.039   ms/op
ClientGrpc.createUser                     sample  291921   3.287 ±  0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.677            ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.269            ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.867            ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.104            ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.118            ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.635            ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.508            ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.120            ms/op
ClientGrpc.existUser                      sample  336152   2.855 ±  0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.496            ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.818            ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420            ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629            ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465            ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.894            ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.932            ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.721            ms/op
ClientGrpc.getUser                        sample  292062   3.287 ±  0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.718            ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.252            ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.879            ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.174            ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.098            ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.060            ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.756            ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.818            ms/op
ClientGrpc.listUser                       sample  224129   4.285 ±  0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.067            ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.133            ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.300            ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.185            ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.733            ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.342            ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.840            ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.623            ms/op
