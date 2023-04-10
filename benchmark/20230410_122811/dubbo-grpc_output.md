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
# Warmup Iteration   1: 4.286 ops/ms
# Warmup Iteration   2: 9.379 ops/ms
# Warmup Iteration   3: 10.234 ops/ms
Iteration   1: 10.759 ops/ms
Iteration   2: 10.734 ops/ms
Iteration   3: 10.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.763 ±(99.9%) 0.585 ops/ms [Average]
  (min, avg, max) = (10.734, 10.763, 10.798), stdev = 0.032
  CI (99.9%): [10.178, 11.349] (assumes normal distribution)


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
# Warmup Iteration   1: 8.098 ops/ms
# Warmup Iteration   2: 10.678 ops/ms
# Warmup Iteration   3: 10.941 ops/ms
Iteration   1: 11.041 ops/ms
Iteration   2: 11.400 ops/ms
Iteration   3: 11.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.234 ±(99.9%) 3.301 ops/ms [Average]
  (min, avg, max) = (11.041, 11.234, 11.400), stdev = 0.181
  CI (99.9%): [7.933, 14.535] (assumes normal distribution)


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
# Warmup Iteration   1: 6.921 ops/ms
# Warmup Iteration   2: 10.272 ops/ms
# Warmup Iteration   3: 10.573 ops/ms
Iteration   1: 10.629 ops/ms
Iteration   2: 10.484 ops/ms
Iteration   3: 10.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.547 ±(99.9%) 1.358 ops/ms [Average]
  (min, avg, max) = (10.484, 10.547, 10.629), stdev = 0.074
  CI (99.9%): [9.189, 11.905] (assumes normal distribution)


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
# Warmup Iteration   1: 5.508 ops/ms
# Warmup Iteration   2: 7.902 ops/ms
# Warmup Iteration   3: 8.182 ops/ms
Iteration   1: 8.141 ops/ms
Iteration   2: 8.211 ops/ms
Iteration   3: 8.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.169 ±(99.9%) 0.679 ops/ms [Average]
  (min, avg, max) = (8.141, 8.169, 8.211), stdev = 0.037
  CI (99.9%): [7.490, 8.848] (assumes normal distribution)


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.003 ms/op
Iteration   1: 2.973 ±(99.9%) 0.003 ms/op
Iteration   2: 2.944 ±(99.9%) 0.003 ms/op
Iteration   3: 2.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.965 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.944, 2.965, 2.979), stdev = 0.019
  CI (99.9%): [2.619, 3.312] (assumes normal distribution)


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.851 ±(99.9%) 0.003 ms/op
Iteration   1: 2.912 ±(99.9%) 0.003 ms/op
Iteration   2: 2.921 ±(99.9%) 0.003 ms/op
Iteration   3: 2.884 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.906 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (2.884, 2.906, 2.921), stdev = 0.020
  CI (99.9%): [2.548, 3.264] (assumes normal distribution)


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
# Warmup Iteration   1: 4.303 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.002 ms/op
Iteration   1: 3.032 ±(99.9%) 0.002 ms/op
Iteration   2: 2.908 ±(99.9%) 0.003 ms/op
Iteration   3: 2.955 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.965 ±(99.9%) 1.144 ms/op [Average]
  (min, avg, max) = (2.908, 2.965, 3.032), stdev = 0.063
  CI (99.9%): [1.821, 4.108] (assumes normal distribution)


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
# Warmup Iteration   1: 5.402 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.011 ms/op
Iteration   1: 3.890 ±(99.9%) 0.016 ms/op
Iteration   2: 3.934 ±(99.9%) 0.018 ms/op
Iteration   3: 3.946 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.923 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (3.890, 3.923, 3.946), stdev = 0.029
  CI (99.9%): [3.391, 4.455] (assumes normal distribution)


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.693 ms/op
                 createUser·p0.9999: 18.825 ms/op
                 createUser·p1.00:   19.235 ms/op

Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.569 ms/op
                 createUser·p0.9999: 14.937 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  8.247 ms/op
                 createUser·p0.9999: 16.834 ms/op
                 createUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317871
  mean =      3.019 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 411 
    [ 1.250,  2.500) = 22493 
    [ 2.500,  3.750) = 281891 
    [ 3.750,  5.000) = 11725 
    [ 5.000,  6.250) = 789 
    [ 6.250,  7.500) = 247 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     19.131 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
Iteration   1: 2.883 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   3.990 ms/op
                 existUser·p0.999:  6.707 ms/op
                 existUser·p0.9999: 15.761 ms/op
                 existUser·p1.00:   16.024 ms/op

Iteration   2: 2.865 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.021 ms/op
                 existUser·p0.9999: 13.872 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.566 ms/op
                 existUser·p0.9999: 23.353 ms/op
                 existUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330941
  mean =      2.901 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43111 
    [ 2.500,  5.000) = 286740 
    [ 5.000,  7.500) = 832 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      7.013 ms/op
     p(99.9900) =     20.268 ms/op
     p(99.9990) =     23.999 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.446 ms/op
                 getUser·p0.9999: 18.168 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   2: 2.985 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.134 ms/op
                 getUser·p0.9999: 15.717 ms/op
                 getUser·p1.00:   16.237 ms/op

Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.465 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  9.232 ms/op
                 getUser·p0.9999: 30.999 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318162
  mean =      3.015 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27066 
    [ 2.500,  5.000) = 289725 
    [ 5.000,  7.500) = 1082 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.109 ms/op
     p(99.9900) =     30.159 ms/op
     p(99.9990) =     31.189 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 4.909 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.010 ms/op
Iteration   1: 3.924 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.522 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  13.156 ms/op
                 listUser·p0.9999: 16.803 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   2: 3.898 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.303 ms/op
                 listUser·p0.9999: 15.561 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   3: 3.852 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 19.031 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246566
  mean =      3.891 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 2538 
    [ 2.500,  3.750) = 119078 
    [ 3.750,  5.000) = 106951 
    [ 5.000,  6.250) = 13043 
    [ 6.250,  7.500) = 3953 
    [ 7.500,  8.750) = 531 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 146 
    [15.000, 16.250) = 84 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.261 ms/op
     p(99.9900) =     17.706 ms/op
     p(99.9990) =     19.582 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.763 ± 0.585  ops/ms
ClientGrpc.existUser                       thrpt       3  11.234 ± 3.301  ops/ms
ClientGrpc.getUser                         thrpt       3  10.547 ± 1.358  ops/ms
ClientGrpc.listUser                        thrpt       3   8.169 ± 0.679  ops/ms
ClientGrpc.createUser                       avgt       3   2.965 ± 0.346   ms/op
ClientGrpc.existUser                        avgt       3   2.906 ± 0.358   ms/op
ClientGrpc.getUser                          avgt       3   2.965 ± 1.144   ms/op
ClientGrpc.listUser                         avgt       3   3.923 ± 0.532   ms/op
ClientGrpc.createUser                     sample  317871   3.019 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.773           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.487           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.088           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.235           ms/op
ClientGrpc.existUser                      sample  330941   2.901 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.598           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.013           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.268           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.150           ms/op
ClientGrpc.getUser                        sample  318162   3.015 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.465           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.109           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.159           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.293           ms/op
ClientGrpc.listUser                       sample  246566   3.891 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.978           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.261           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.706           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.694           ms/op
