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
# Warmup Iteration   1: 4.153 ops/ms
# Warmup Iteration   2: 9.081 ops/ms
# Warmup Iteration   3: 10.375 ops/ms
Iteration   1: 10.629 ops/ms
Iteration   2: 10.423 ops/ms
Iteration   3: 10.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.534 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (10.423, 10.534, 10.629), stdev = 0.104
  CI (99.9%): [8.638, 12.429] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.682 ops/ms
# Warmup Iteration   2: 10.571 ops/ms
# Warmup Iteration   3: 10.893 ops/ms
Iteration   1: 10.806 ops/ms
Iteration   2: 11.077 ops/ms
Iteration   3: 10.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.956 ±(99.9%) 2.517 ops/ms [Average]
  (min, avg, max) = (10.806, 10.956, 11.077), stdev = 0.138
  CI (99.9%): [8.439, 13.473] (assumes normal distribution)


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
# Warmup Iteration   1: 7.275 ops/ms
# Warmup Iteration   2: 9.914 ops/ms
# Warmup Iteration   3: 10.249 ops/ms
Iteration   1: 10.487 ops/ms
Iteration   2: 10.318 ops/ms
Iteration   3: 10.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.439 ±(99.9%) 1.909 ops/ms [Average]
  (min, avg, max) = (10.318, 10.439, 10.510), stdev = 0.105
  CI (99.9%): [8.530, 12.347] (assumes normal distribution)


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
# Warmup Iteration   1: 6.003 ops/ms
# Warmup Iteration   2: 7.783 ops/ms
# Warmup Iteration   3: 8.119 ops/ms
Iteration   1: 8.039 ops/ms
Iteration   2: 8.067 ops/ms
Iteration   3: 8.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.077 ±(99.9%) 0.795 ops/ms [Average]
  (min, avg, max) = (8.039, 8.077, 8.125), stdev = 0.044
  CI (99.9%): [7.282, 8.872] (assumes normal distribution)


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
# Warmup Iteration   1: 3.969 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.003 ms/op
Iteration   1: 3.005 ±(99.9%) 0.008 ms/op
Iteration   2: 3.023 ±(99.9%) 0.003 ms/op
Iteration   3: 2.985 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.005 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (2.985, 3.005, 3.023), stdev = 0.019
  CI (99.9%): [2.660, 3.349] (assumes normal distribution)


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.837 ±(99.9%) 0.004 ms/op
Iteration   1: 2.849 ±(99.9%) 0.004 ms/op
Iteration   2: 2.717 ±(99.9%) 0.004 ms/op
Iteration   3: 2.909 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.825 ±(99.9%) 1.795 ms/op [Average]
  (min, avg, max) = (2.717, 2.825, 2.909), stdev = 0.098
  CI (99.9%): [1.030, 4.620] (assumes normal distribution)


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.004 ms/op
Iteration   1: 3.012 ±(99.9%) 0.003 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 3.059 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.021 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (2.994, 3.021, 3.059), stdev = 0.033
  CI (99.9%): [2.411, 3.632] (assumes normal distribution)


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
# Warmup Iteration   1: 5.214 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.016 ms/op
Iteration   1: 3.968 ±(99.9%) 0.016 ms/op
Iteration   2: 3.942 ±(99.9%) 0.014 ms/op
Iteration   3: 3.929 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.946 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (3.929, 3.946, 3.968), stdev = 0.020
  CI (99.9%): [3.580, 4.313] (assumes normal distribution)


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
# Warmup Iteration   1: 3.713 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.007 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.796 ms/op
                 createUser·p0.9999: 17.936 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   2: 3.005 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.589 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.682 ms/op
                 createUser·p0.9999: 21.945 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  7.735 ms/op
                 createUser·p0.9999: 17.327 ms/op
                 createUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319185
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26750 
    [ 2.500,  5.000) = 290863 
    [ 5.000,  7.500) = 1195 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.732 ms/op
     p(99.9900) =     21.012 ms/op
     p(99.9990) =     22.237 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 3.919 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
Iteration   1: 2.933 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.485 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  8.081 ms/op
                 existUser·p0.9999: 21.793 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   2: 2.954 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.231 ms/op
                 existUser·p0.9999: 15.335 ms/op
                 existUser·p1.00:   16.253 ms/op

Iteration   3: 2.946 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  7.745 ms/op
                 existUser·p0.9999: 16.302 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326026
  mean =      2.945 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31754 
    [ 2.500,  5.000) = 292495 
    [ 5.000,  7.500) = 1430 
    [ 7.500, 10.000) = 187 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      7.578 ms/op
     p(99.9900) =     18.897 ms/op
     p(99.9990) =     22.036 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 4.109 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.006 ms/op
Iteration   1: 3.110 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  8.210 ms/op
                 getUser·p0.9999: 15.300 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.987 ms/op
                 getUser·p0.9999: 21.529 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.341 ms/op
                 getUser·p0.9999: 14.690 ms/op
                 getUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310978
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22879 
    [ 2.500,  5.000) = 286288 
    [ 5.000,  7.500) = 1426 
    [ 7.500, 10.000) = 161 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.766 ms/op
     p(99.9900) =     19.838 ms/op
     p(99.9990) =     22.275 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 5.011 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.011 ms/op
Iteration   1: 4.117 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.751 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  13.145 ms/op
                 listUser·p0.9999: 14.699 ms/op
                 listUser·p1.00:   15.073 ms/op

Iteration   2: 4.094 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 15.125 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   3: 4.101 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   7.235 ms/op
                 listUser·p0.999:  15.156 ms/op
                 listUser·p0.9999: 21.149 ms/op
                 listUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233873
  mean =      4.104 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2362 
    [ 2.500,  5.000) = 205414 
    [ 5.000,  7.500) = 24262 
    [ 7.500, 10.000) = 1308 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 291 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     14.076 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     21.528 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.534 ± 1.896  ops/ms
ClientGrpc.existUser                       thrpt       3  10.956 ± 2.517  ops/ms
ClientGrpc.getUser                         thrpt       3  10.439 ± 1.909  ops/ms
ClientGrpc.listUser                        thrpt       3   8.077 ± 0.795  ops/ms
ClientGrpc.createUser                       avgt       3   3.005 ± 0.344   ms/op
ClientGrpc.existUser                        avgt       3   2.825 ± 1.795   ms/op
ClientGrpc.getUser                          avgt       3   3.021 ± 0.610   ms/op
ClientGrpc.listUser                         avgt       3   3.946 ± 0.366   ms/op
ClientGrpc.createUser                     sample  319185   3.007 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.570           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.732           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.012           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.348           ms/op
ClientGrpc.existUser                      sample  326026   2.945 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.485           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.578           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.897           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.184           ms/op
ClientGrpc.getUser                        sample  310978   3.087 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.658           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.766           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.838           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.381           ms/op
ClientGrpc.listUser                       sample  233873   4.104 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.751           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.201           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.076           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.825           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.627           ms/op
