# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ops/ms
# Warmup Iteration   2: 8.953 ops/ms
# Warmup Iteration   3: 9.950 ops/ms
Iteration   1: 10.553 ops/ms
Iteration   2: 10.646 ops/ms
Iteration   3: 10.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.579 ±(99.9%) 1.070 ops/ms [Average]
  (min, avg, max) = (10.538, 10.579, 10.646), stdev = 0.059
  CI (99.9%): [9.509, 11.649] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.341 ops/ms
# Warmup Iteration   2: 10.429 ops/ms
# Warmup Iteration   3: 11.048 ops/ms
Iteration   1: 11.231 ops/ms
Iteration   2: 11.077 ops/ms
Iteration   3: 10.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.025 ±(99.9%) 4.328 ops/ms [Average]
  (min, avg, max) = (10.766, 11.025, 11.231), stdev = 0.237
  CI (99.9%): [6.696, 15.353] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.786 ops/ms
# Warmup Iteration   2: 10.103 ops/ms
# Warmup Iteration   3: 10.568 ops/ms
Iteration   1: 10.653 ops/ms
Iteration   2: 10.664 ops/ms
Iteration   3: 10.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.599 ±(99.9%) 1.873 ops/ms [Average]
  (min, avg, max) = (10.481, 10.599, 10.664), stdev = 0.103
  CI (99.9%): [8.727, 12.472] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.475 ops/ms
# Warmup Iteration   2: 7.887 ops/ms
# Warmup Iteration   3: 8.141 ops/ms
Iteration   1: 8.174 ops/ms
Iteration   2: 8.201 ops/ms
Iteration   3: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.221 ±(99.9%) 1.087 ops/ms [Average]
  (min, avg, max) = (8.174, 8.221, 8.288), stdev = 0.060
  CI (99.9%): [7.134, 9.307] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.172 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.003 ms/op
Iteration   1: 3.059 ±(99.9%) 0.003 ms/op
Iteration   2: 2.959 ±(99.9%) 0.005 ms/op
Iteration   3: 3.038 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.019 ±(99.9%) 0.964 ms/op [Average]
  (min, avg, max) = (2.959, 3.019, 3.059), stdev = 0.053
  CI (99.9%): [2.054, 3.983] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.912 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.003 ms/op
Iteration   1: 2.930 ±(99.9%) 0.002 ms/op
Iteration   2: 2.860 ±(99.9%) 0.003 ms/op
Iteration   3: 2.913 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.901 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (2.860, 2.901, 2.930), stdev = 0.037
  CI (99.9%): [2.235, 3.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.871 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.004 ms/op
Iteration   1: 3.006 ±(99.9%) 0.004 ms/op
Iteration   2: 3.016 ±(99.9%) 0.004 ms/op
Iteration   3: 3.013 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.012 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (3.006, 3.012, 3.016), stdev = 0.005
  CI (99.9%): [2.915, 3.109] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.753 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.012 ms/op
Iteration   1: 3.940 ±(99.9%) 0.015 ms/op
Iteration   2: 3.939 ±(99.9%) 0.034 ms/op
Iteration   3: 3.914 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.931 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.914, 3.931, 3.940), stdev = 0.015
  CI (99.9%): [3.661, 4.200] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.438 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  6.668 ms/op
                 createUser·p0.9999: 18.186 ms/op
                 createUser·p1.00:   18.678 ms/op

Iteration   2: 3.021 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  7.076 ms/op
                 createUser·p0.9999: 21.476 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  17.990 ms/op
                 createUser·p0.9999: 22.347 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316932
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19756 
    [ 2.500,  5.000) = 295836 
    [ 5.000,  7.500) = 1017 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.372 ms/op
     p(99.9000) =      7.619 ms/op
     p(99.9900) =     21.375 ms/op
     p(99.9990) =     23.291 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.960 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.004 ms/op
Iteration   1: 2.938 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  8.732 ms/op
                 existUser·p0.9999: 12.339 ms/op
                 existUser·p1.00:   12.698 ms/op

Iteration   2: 2.938 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.276 ms/op
                 existUser·p0.9999: 13.732 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.915 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   3.961 ms/op
                 existUser·p0.999:  7.555 ms/op
                 existUser·p0.9999: 15.244 ms/op
                 existUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327545
  mean =      2.931 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 528 
    [ 1.250,  2.500) = 41869 
    [ 2.500,  3.750) = 274236 
    [ 3.750,  5.000) = 10043 
    [ 5.000,  6.250) = 275 
    [ 6.250,  7.500) = 209 
    [ 7.500,  8.750) = 116 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.175 ms/op
     p(99.9900) =     14.197 ms/op
     p(99.9990) =     16.379 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.578 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
Iteration   1: 3.046 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  6.914 ms/op
                 getUser·p0.9999: 13.779 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.493 ms/op
                 getUser·p0.999:  6.023 ms/op
                 getUser·p0.9999: 14.508 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   3: 3.015 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  8.451 ms/op
                 getUser·p0.9999: 19.949 ms/op
                 getUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316007
  mean =      3.036 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26400 
    [ 2.500,  5.000) = 288119 
    [ 5.000,  7.500) = 1173 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.496 ms/op
     p(99.9900) =     19.543 ms/op
     p(99.9990) =     20.540 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.001 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.012 ms/op
Iteration   1: 3.945 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.922 ms/op
                 listUser·p0.9999: 16.018 ms/op
                 listUser·p1.00:   16.253 ms/op

Iteration   2: 3.856 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 25.838 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   3: 3.933 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.346 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 21.843 ms/op
                 listUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245356
  mean =      3.911 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3129 
    [ 2.500,  5.000) = 219682 
    [ 5.000,  7.500) = 21383 
    [ 7.500, 10.000) = 742 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     15.099 ms/op
     p(99.9900) =     21.360 ms/op
     p(99.9990) =     26.149 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.579 ± 1.070  ops/ms
ClientGrpc.existUser                       thrpt       3  11.025 ± 4.328  ops/ms
ClientGrpc.getUser                         thrpt       3  10.599 ± 1.873  ops/ms
ClientGrpc.listUser                        thrpt       3   8.221 ± 1.087  ops/ms
ClientGrpc.createUser                       avgt       3   3.019 ± 0.964   ms/op
ClientGrpc.existUser                        avgt       3   2.901 ± 0.666   ms/op
ClientGrpc.getUser                          avgt       3   3.012 ± 0.097   ms/op
ClientGrpc.listUser                         avgt       3   3.931 ± 0.269   ms/op
ClientGrpc.createUser                     sample  316932   3.030 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.542           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.372           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.619           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.375           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.658           ms/op
ClientGrpc.existUser                      sample  327545   2.931 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.550           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.175           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.197           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.515           ms/op
ClientGrpc.getUser                        sample  316007   3.036 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.719           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.496           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.543           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.546           ms/op
ClientGrpc.listUser                       sample  245356   3.911 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.962           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.099           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.360           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.001           ms/op
