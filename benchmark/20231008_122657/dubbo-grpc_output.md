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
# Warmup Iteration   1: 4.441 ops/ms
# Warmup Iteration   2: 8.528 ops/ms
# Warmup Iteration   3: 9.721 ops/ms
Iteration   1: 9.996 ops/ms
Iteration   2: 10.193 ops/ms
Iteration   3: 10.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.132 ±(99.9%) 2.151 ops/ms [Average]
  (min, avg, max) = (9.996, 10.132, 10.206), stdev = 0.118
  CI (99.9%): [7.981, 12.283] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.534 ops/ms
# Warmup Iteration   2: 10.306 ops/ms
# Warmup Iteration   3: 10.490 ops/ms
Iteration   1: 10.937 ops/ms
Iteration   2: 10.758 ops/ms
Iteration   3: 10.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.749 ±(99.9%) 3.514 ops/ms [Average]
  (min, avg, max) = (10.553, 10.749, 10.937), stdev = 0.193
  CI (99.9%): [7.235, 14.263] (assumes normal distribution)


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
# Warmup Iteration   1: 6.610 ops/ms
# Warmup Iteration   2: 9.768 ops/ms
# Warmup Iteration   3: 9.933 ops/ms
Iteration   1: 10.106 ops/ms
Iteration   2: 10.102 ops/ms
Iteration   3: 10.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.110 ±(99.9%) 0.182 ops/ms [Average]
  (min, avg, max) = (10.102, 10.110, 10.121), stdev = 0.010
  CI (99.9%): [9.928, 10.292] (assumes normal distribution)


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
# Warmup Iteration   1: 5.069 ops/ms
# Warmup Iteration   2: 7.584 ops/ms
# Warmup Iteration   3: 7.764 ops/ms
Iteration   1: 7.740 ops/ms
Iteration   2: 7.923 ops/ms
Iteration   3: 7.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.806 ±(99.9%) 1.852 ops/ms [Average]
  (min, avg, max) = (7.740, 7.806, 7.923), stdev = 0.101
  CI (99.9%): [5.955, 9.658] (assumes normal distribution)


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
# Warmup Iteration   1: 4.473 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.003 ms/op
Iteration   1: 3.227 ±(99.9%) 0.004 ms/op
Iteration   2: 3.054 ±(99.9%) 0.003 ms/op
Iteration   3: 3.105 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.129 ±(99.9%) 1.624 ms/op [Average]
  (min, avg, max) = (3.054, 3.129, 3.227), stdev = 0.089
  CI (99.9%): [1.505, 4.752] (assumes normal distribution)


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
# Warmup Iteration   1: 4.248 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.004 ms/op
Iteration   1: 2.936 ±(99.9%) 0.004 ms/op
Iteration   2: 2.981 ±(99.9%) 0.004 ms/op
Iteration   3: 3.030 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.982 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (2.936, 2.982, 3.030), stdev = 0.047
  CI (99.9%): [2.124, 3.841] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.280 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.003 ms/op
Iteration   1: 3.206 ±(99.9%) 0.007 ms/op
Iteration   2: 3.143 ±(99.9%) 0.004 ms/op
Iteration   3: 3.164 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.171 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (3.143, 3.171, 3.206), stdev = 0.032
  CI (99.9%): [2.589, 3.753] (assumes normal distribution)


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
# Warmup Iteration   1: 5.283 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.030 ms/op
Iteration   1: 3.993 ±(99.9%) 0.017 ms/op
Iteration   2: 3.968 ±(99.9%) 0.016 ms/op
Iteration   3: 3.964 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.975 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (3.964, 3.975, 3.993), stdev = 0.016
  CI (99.9%): [3.682, 4.269] (assumes normal distribution)


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.008 ms/op
Iteration   1: 3.128 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.946 ms/op
                 createUser·p0.9999: 14.771 ms/op
                 createUser·p1.00:   15.073 ms/op

Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.618 ms/op
                 createUser·p0.999:  9.426 ms/op
                 createUser·p0.9999: 15.177 ms/op
                 createUser·p1.00:   15.499 ms/op

Iteration   3: 3.134 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  14.673 ms/op
                 createUser·p0.9999: 27.681 ms/op
                 createUser·p1.00:   49.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307999
  mean =      3.120 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 305672 
    [ 5.000, 10.000) = 1968 
    [10.000, 15.000) = 250 
    [15.000, 20.000) = 42 
    [20.000, 25.000) = 34 
    [25.000, 30.000) = 30 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     26.942 ms/op
     p(99.9990) =     30.171 ms/op
     p(99.9999) =     49.938 ms/op
    p(100.0000) =     49.938 ms/op


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
Iteration   1: 2.938 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  10.981 ms/op
                 existUser·p0.9999: 20.480 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  8.190 ms/op
                 existUser·p0.9999: 17.826 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   3: 2.993 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.234 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322886
  mean =      2.973 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29146 
    [ 2.500,  5.000) = 291847 
    [ 5.000,  7.500) = 1377 
    [ 7.500, 10.000) = 234 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.113 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     22.735 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.313 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
Iteration   1: 3.142 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  16.193 ms/op
                 getUser·p0.9999: 37.290 ms/op
                 getUser·p1.00:   38.601 ms/op

Iteration   2: 3.148 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.320 ms/op
                 getUser·p0.9999: 22.343 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.113 ms/op
                 getUser·p0.9999: 25.264 ms/op
                 getUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305429
  mean =      3.143 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9074 
    [ 2.500,  5.000) = 294527 
    [ 5.000,  7.500) = 1296 
    [ 7.500, 10.000) = 222 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     10.233 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     37.749 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


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
# Warmup Iteration   1: 5.227 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.010 ms/op
Iteration   1: 4.004 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  12.799 ms/op
                 listUser·p0.9999: 17.498 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   2: 4.006 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 19.957 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   3: 3.984 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.783 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  15.805 ms/op
                 listUser·p0.9999: 21.364 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240055
  mean =      3.998 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2871 
    [ 2.500,  5.000) = 219774 
    [ 5.000,  7.500) = 15911 
    [ 7.500, 10.000) = 756 
    [10.000, 12.500) = 309 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.285 ms/op
     p(99.9900) =     20.119 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.132 ± 2.151  ops/ms
ClientGrpc.existUser                       thrpt       3  10.749 ± 3.514  ops/ms
ClientGrpc.getUser                         thrpt       3  10.110 ± 0.182  ops/ms
ClientGrpc.listUser                        thrpt       3   7.806 ± 1.852  ops/ms
ClientGrpc.createUser                       avgt       3   3.129 ± 1.624   ms/op
ClientGrpc.existUser                        avgt       3   2.982 ± 0.858   ms/op
ClientGrpc.getUser                          avgt       3   3.171 ± 0.582   ms/op
ClientGrpc.listUser                         avgt       3   3.975 ± 0.293   ms/op
ClientGrpc.createUser                     sample  307999   3.120 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.841           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.485           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.942           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          49.938           ms/op
ClientGrpc.existUser                      sample  322886   2.973 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.627           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.113           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.793           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.364           ms/op
ClientGrpc.getUser                        sample  305429   3.143 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.657           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.233           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.914           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          38.601           ms/op
ClientGrpc.listUser                       sample  240055   3.998 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.783           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.285           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.119           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.463           ms/op
