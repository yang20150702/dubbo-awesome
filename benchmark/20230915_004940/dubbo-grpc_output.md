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
# Warmup Iteration   1: 2.519 ops/ms
# Warmup Iteration   2: 6.042 ops/ms
# Warmup Iteration   3: 7.329 ops/ms
Iteration   1: 7.677 ops/ms
Iteration   2: 7.725 ops/ms
Iteration   3: 7.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.761 ±(99.9%) 1.933 ops/ms [Average]
  (min, avg, max) = (7.677, 7.761, 7.880), stdev = 0.106
  CI (99.9%): [5.828, 9.694] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.135 ops/ms
# Warmup Iteration   2: 7.303 ops/ms
# Warmup Iteration   3: 7.882 ops/ms
Iteration   1: 8.295 ops/ms
Iteration   2: 8.211 ops/ms
Iteration   3: 8.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.258 ±(99.9%) 0.781 ops/ms [Average]
  (min, avg, max) = (8.211, 8.258, 8.295), stdev = 0.043
  CI (99.9%): [7.478, 9.039] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.692 ops/ms
# Warmup Iteration   2: 7.232 ops/ms
# Warmup Iteration   3: 7.512 ops/ms
Iteration   1: 7.617 ops/ms
Iteration   2: 7.693 ops/ms
Iteration   3: 7.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.603 ±(99.9%) 1.794 ops/ms [Average]
  (min, avg, max) = (7.498, 7.603, 7.693), stdev = 0.098
  CI (99.9%): [5.809, 9.396] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.588 ops/ms
# Warmup Iteration   2: 5.803 ops/ms
# Warmup Iteration   3: 5.967 ops/ms
Iteration   1: 6.033 ops/ms
Iteration   2: 6.110 ops/ms
Iteration   3: 6.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.122 ±(99.9%) 1.735 ops/ms [Average]
  (min, avg, max) = (6.033, 6.122, 6.222), stdev = 0.095
  CI (99.9%): [4.387, 7.857] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.973 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.247 ±(99.9%) 0.011 ms/op
Iteration   1: 4.253 ±(99.9%) 0.003 ms/op
Iteration   2: 4.373 ±(99.9%) 0.001 ms/op
Iteration   3: 4.200 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.275 ±(99.9%) 1.623 ms/op [Average]
  (min, avg, max) = (4.200, 4.275, 4.373), stdev = 0.089
  CI (99.9%): [2.653, 5.898] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.768 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.003 ms/op
Iteration   1: 4.030 ±(99.9%) 0.002 ms/op
Iteration   2: 4.092 ±(99.9%) 0.003 ms/op
Iteration   3: 3.863 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.995 ±(99.9%) 2.156 ms/op [Average]
  (min, avg, max) = (3.863, 3.995, 4.092), stdev = 0.118
  CI (99.9%): [1.839, 6.152] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.607 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.526 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.276 ±(99.9%) 0.003 ms/op
Iteration   1: 4.224 ±(99.9%) 0.002 ms/op
Iteration   2: 4.618 ±(99.9%) 0.006 ms/op
Iteration   3: 4.188 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.343 ±(99.9%) 4.355 ms/op [Average]
  (min, avg, max) = (4.188, 4.343, 4.618), stdev = 0.239
  CI (99.9%): [≈ 0, 8.698] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.748 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.601 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.455 ±(99.9%) 0.021 ms/op
Iteration   1: 5.298 ±(99.9%) 0.012 ms/op
Iteration   2: 5.336 ±(99.9%) 0.010 ms/op
Iteration   3: 5.347 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.327 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (5.298, 5.327, 5.347), stdev = 0.026
  CI (99.9%): [4.858, 5.797] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.689 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.394 ±(99.9%) 0.013 ms/op
Iteration   1: 4.170 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   4.076 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   5.620 ms/op
                 createUser·p0.99:   7.398 ms/op
                 createUser·p0.999:  11.607 ms/op
                 createUser·p0.9999: 23.341 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 4.313 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.816 ms/op
                 createUser·p0.99:   7.799 ms/op
                 createUser·p0.999:  12.899 ms/op
                 createUser·p0.9999: 27.230 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   3: 4.212 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   4.088 ms/op
                 createUser·p0.90:   5.202 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.553 ms/op
                 createUser·p0.999:  11.207 ms/op
                 createUser·p0.9999: 30.318 ms/op
                 createUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227094
  mean =      4.231 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4276 
    [ 2.500,  5.000) = 188166 
    [ 5.000,  7.500) = 32260 
    [ 7.500, 10.000) = 1822 
    [10.000, 12.500) = 420 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     11.600 ms/op
     p(99.9900) =     28.279 ms/op
     p(99.9990) =     31.973 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.826 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.011 ms/op
Iteration   1: 4.054 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   3.924 ms/op
                 existUser·p0.90:   5.079 ms/op
                 existUser·p0.95:   5.472 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  10.125 ms/op
                 existUser·p0.9999: 15.993 ms/op
                 existUser·p1.00:   16.335 ms/op

Iteration   2: 3.841 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.030 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  12.660 ms/op
                 existUser·p0.9999: 15.844 ms/op
                 existUser·p1.00:   16.269 ms/op

Iteration   3: 3.917 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 20.185 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 243821
  mean =      3.935 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5248 
    [ 2.500,  5.000) = 218929 
    [ 5.000,  7.500) = 17874 
    [ 7.500, 10.000) = 1413 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     11.357 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     20.302 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.210 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.011 ms/op
Iteration   1: 4.119 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   5.046 ms/op
                 getUser·p0.95:   5.481 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  21.835 ms/op
                 getUser·p0.9999: 89.653 ms/op
                 getUser·p1.00:   90.964 ms/op

Iteration   2: 4.169 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.136 ms/op
                 getUser·p0.95:   5.568 ms/op
                 getUser·p0.99:   7.340 ms/op
                 getUser·p0.999:  11.452 ms/op
                 getUser·p0.9999: 17.804 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   3: 4.137 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   5.079 ms/op
                 getUser·p0.95:   5.478 ms/op
                 getUser·p0.99:   7.362 ms/op
                 getUser·p0.999:  13.839 ms/op
                 getUser·p0.9999: 25.699 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 231709
  mean =      4.141 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 231147 
    [ 10.000,  20.000) = 430 
    [ 20.000,  30.000) = 92 
    [ 30.000,  40.000) = 4 
    [ 40.000,  50.000) = 5 
    [ 50.000,  60.000) = 5 
    [ 60.000,  70.000) = 6 
    [ 70.000,  80.000) = 5 
    [ 80.000,  90.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     12.850 ms/op
     p(99.9900) =     65.214 ms/op
     p(99.9990) =     89.784 ms/op
     p(99.9999) =     90.964 ms/op
    p(100.0000) =     90.964 ms/op


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
# Warmup Iteration   1: 7.937 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.789 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.437 ±(99.9%) 0.019 ms/op
Iteration   1: 5.311 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.518 ms/op
                 listUser·p0.50:   5.046 ms/op
                 listUser·p0.90:   6.988 ms/op
                 listUser·p0.95:   7.979 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  15.430 ms/op
                 listUser·p0.9999: 18.117 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 5.383 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   6.595 ms/op
                 listUser·p0.95:   7.660 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  15.886 ms/op
                 listUser·p0.9999: 18.780 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 5.484 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   10.880 ms/op
                 listUser·p0.999:  20.414 ms/op
                 listUser·p0.9999: 33.278 ms/op
                 listUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 177899
  mean =      5.392 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 196 
    [ 2.500,  5.000) = 77128 
    [ 5.000,  7.500) = 88010 
    [ 7.500, 10.000) = 10208 
    [10.000, 12.500) = 1625 
    [12.500, 15.000) = 417 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      8.004 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     32.513 ms/op
     p(99.9990) =     34.704 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.761 ± 1.933  ops/ms
ClientGrpc.existUser                       thrpt       3   8.258 ± 0.781  ops/ms
ClientGrpc.getUser                         thrpt       3   7.603 ± 1.794  ops/ms
ClientGrpc.listUser                        thrpt       3   6.122 ± 1.735  ops/ms
ClientGrpc.createUser                       avgt       3   4.275 ± 1.623   ms/op
ClientGrpc.existUser                        avgt       3   3.995 ± 2.156   ms/op
ClientGrpc.getUser                          avgt       3   4.343 ± 4.355   ms/op
ClientGrpc.listUser                         avgt       3   5.327 ± 0.470   ms/op
ClientGrpc.createUser                     sample  227094   4.231 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.083           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.116           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.267           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.710           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.594           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.600           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.279           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.113           ms/op
ClientGrpc.existUser                      sample  243821   3.935 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.930           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.874           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.276           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.955           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.357           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.825           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.316           ms/op
ClientGrpc.getUser                        sample  231709   4.141 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.110           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.087           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.505           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.266           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.850           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          65.214           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          90.964           ms/op
ClientGrpc.listUser                       sample  177899   5.392 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.073           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.004           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.519           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.925           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.513           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.521           ms/op
