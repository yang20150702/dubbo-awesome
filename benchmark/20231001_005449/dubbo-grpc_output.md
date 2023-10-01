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
# Warmup Iteration   1: 4.041 ops/ms
# Warmup Iteration   2: 8.501 ops/ms
# Warmup Iteration   3: 9.689 ops/ms
Iteration   1: 10.070 ops/ms
Iteration   2: 10.116 ops/ms
Iteration   3: 10.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.119 ±(99.9%) 0.908 ops/ms [Average]
  (min, avg, max) = (10.070, 10.119, 10.170), stdev = 0.050
  CI (99.9%): [9.211, 11.027] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.871 ops/ms
# Warmup Iteration   2: 10.117 ops/ms
# Warmup Iteration   3: 10.504 ops/ms
Iteration   1: 10.782 ops/ms
Iteration   2: 10.731 ops/ms
Iteration   3: 10.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.774 ±(99.9%) 0.707 ops/ms [Average]
  (min, avg, max) = (10.731, 10.774, 10.808), stdev = 0.039
  CI (99.9%): [10.067, 11.481] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.648 ops/ms
# Warmup Iteration   2: 9.619 ops/ms
# Warmup Iteration   3: 10.134 ops/ms
Iteration   1: 10.126 ops/ms
Iteration   2: 10.178 ops/ms
Iteration   3: 10.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.128 ±(99.9%) 0.909 ops/ms [Average]
  (min, avg, max) = (10.078, 10.128, 10.178), stdev = 0.050
  CI (99.9%): [9.219, 11.036] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.455 ops/ms
# Warmup Iteration   2: 7.662 ops/ms
# Warmup Iteration   3: 7.929 ops/ms
Iteration   1: 7.886 ops/ms
Iteration   2: 8.208 ops/ms
Iteration   3: 7.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.019 ±(99.9%) 3.073 ops/ms [Average]
  (min, avg, max) = (7.886, 8.019, 8.208), stdev = 0.168
  CI (99.9%): [4.946, 11.092] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.763 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.003 ms/op
Iteration   1: 3.214 ±(99.9%) 0.002 ms/op
Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
Iteration   3: 3.118 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.150 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (3.117, 3.150, 3.214), stdev = 0.055
  CI (99.9%): [2.139, 4.160] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.132 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.002 ms/op
Iteration   1: 3.022 ±(99.9%) 0.005 ms/op
Iteration   2: 2.965 ±(99.9%) 0.003 ms/op
Iteration   3: 3.015 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.001 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (2.965, 3.001, 3.022), stdev = 0.031
  CI (99.9%): [2.433, 3.569] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.404 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.006 ms/op
Iteration   1: 3.123 ±(99.9%) 0.003 ms/op
Iteration   2: 3.154 ±(99.9%) 0.005 ms/op
Iteration   3: 3.125 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.134 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.123, 3.134, 3.154), stdev = 0.017
  CI (99.9%): [2.819, 3.448] (assumes normal distribution)


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
# Warmup Iteration   1: 5.344 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.036 ms/op
Iteration   1: 3.980 ±(99.9%) 0.012 ms/op
Iteration   2: 3.992 ±(99.9%) 0.020 ms/op
Iteration   3: 3.932 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.968 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.932, 3.968, 3.992), stdev = 0.032
  CI (99.9%): [3.390, 4.546] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.678 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.007 ms/op
Iteration   1: 3.123 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  10.805 ms/op
                 createUser·p0.9999: 16.204 ms/op
                 createUser·p1.00:   16.597 ms/op

Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.387 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  9.723 ms/op
                 createUser·p0.9999: 17.591 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  9.993 ms/op
                 createUser·p0.9999: 21.946 ms/op
                 createUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306844
  mean =      3.128 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13149 
    [ 2.500,  5.000) = 291234 
    [ 5.000,  7.500) = 1789 
    [ 7.500, 10.000) = 361 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.387 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.849 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =     10.108 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.297 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
Iteration   1: 3.044 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  8.415 ms/op
                 existUser·p0.9999: 19.103 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  10.151 ms/op
                 existUser·p0.9999: 17.138 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   3: 3.060 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  11.820 ms/op
                 existUser·p0.9999: 24.576 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315587
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22679 
    [ 2.500,  5.000) = 291172 
    [ 5.000,  7.500) = 1075 
    [ 7.500, 10.000) = 341 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =     10.132 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 16.154 ms/op
                 getUser·p1.00:   19.202 ms/op

Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  9.321 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.209 ms/op
                 getUser·p0.9999: 16.744 ms/op
                 getUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306076
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12328 
    [ 2.500,  5.000) = 291444 
    [ 5.000,  7.500) = 1850 
    [ 7.500, 10.000) = 182 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      9.041 ms/op
     p(99.9900) =     17.085 ms/op
     p(99.9990) =     22.270 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 5.634 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.012 ms/op
Iteration   1: 4.016 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.764 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  16.515 ms/op
                 listUser·p0.9999: 19.746 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 3.917 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.473 ms/op
                 listUser·p0.9999: 17.947 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   3: 4.045 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240424
  mean =      3.992 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2499 
    [ 2.500,  5.000) = 220894 
    [ 5.000,  7.500) = 15675 
    [ 7.500, 10.000) = 793 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     15.886 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.119 ± 0.908  ops/ms
ClientGrpc.existUser                       thrpt       3  10.774 ± 0.707  ops/ms
ClientGrpc.getUser                         thrpt       3  10.128 ± 0.909  ops/ms
ClientGrpc.listUser                        thrpt       3   8.019 ± 3.073  ops/ms
ClientGrpc.createUser                       avgt       3   3.150 ± 1.010   ms/op
ClientGrpc.existUser                        avgt       3   3.001 ± 0.568   ms/op
ClientGrpc.getUser                          avgt       3   3.134 ± 0.315   ms/op
ClientGrpc.listUser                         avgt       3   3.968 ± 0.578   ms/op
ClientGrpc.createUser                     sample  306844   3.128 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.387           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.849           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.108           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.135           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.364           ms/op
ClientGrpc.existUser                      sample  315587   3.043 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.763           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.132           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.873           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.740           ms/op
ClientGrpc.getUser                        sample  306076   3.134 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.658           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.041           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.085           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.479           ms/op
ClientGrpc.listUser                       sample  240424   3.992 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.972           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.886           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.300           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.037           ms/op
