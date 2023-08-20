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
# Warmup Iteration   1: 4.856 ops/ms
# Warmup Iteration   2: 9.502 ops/ms
# Warmup Iteration   3: 10.439 ops/ms
Iteration   1: 10.663 ops/ms
Iteration   2: 10.721 ops/ms
Iteration   3: 10.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.668 ±(99.9%) 0.932 ops/ms [Average]
  (min, avg, max) = (10.619, 10.668, 10.721), stdev = 0.051
  CI (99.9%): [9.736, 11.600] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.857 ops/ms
# Warmup Iteration   2: 10.653 ops/ms
# Warmup Iteration   3: 11.045 ops/ms
Iteration   1: 11.411 ops/ms
Iteration   2: 11.297 ops/ms
Iteration   3: 11.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.375 ±(99.9%) 1.233 ops/ms [Average]
  (min, avg, max) = (11.297, 11.375, 11.416), stdev = 0.068
  CI (99.9%): [10.142, 12.607] (assumes normal distribution)


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
# Warmup Iteration   1: 7.489 ops/ms
# Warmup Iteration   2: 10.319 ops/ms
# Warmup Iteration   3: 10.355 ops/ms
Iteration   1: 10.933 ops/ms
Iteration   2: 10.720 ops/ms
Iteration   3: 10.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.803 ±(99.9%) 2.081 ops/ms [Average]
  (min, avg, max) = (10.720, 10.803, 10.933), stdev = 0.114
  CI (99.9%): [8.722, 12.884] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.871 ops/ms
# Warmup Iteration   2: 8.188 ops/ms
# Warmup Iteration   3: 8.124 ops/ms
Iteration   1: 8.210 ops/ms
Iteration   2: 8.239 ops/ms
Iteration   3: 8.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.206 ±(99.9%) 0.635 ops/ms [Average]
  (min, avg, max) = (8.169, 8.206, 8.239), stdev = 0.035
  CI (99.9%): [7.571, 8.841] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.819 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.004 ms/op
Iteration   1: 2.993 ±(99.9%) 0.026 ms/op
Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
Iteration   3: 2.945 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.983 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (2.945, 2.983, 3.010), stdev = 0.033
  CI (99.9%): [2.373, 3.593] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.388 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.003 ms/op
Iteration   1: 2.926 ±(99.9%) 0.002 ms/op
Iteration   2: 2.954 ±(99.9%) 0.003 ms/op
Iteration   3: 2.965 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.948 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (2.926, 2.948, 2.965), stdev = 0.020
  CI (99.9%): [2.582, 3.314] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.066 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.003 ms/op
Iteration   1: 2.967 ±(99.9%) 0.005 ms/op
Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
Iteration   3: 2.977 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.985 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.967, 2.985, 3.012), stdev = 0.023
  CI (99.9%): [2.559, 3.411] (assumes normal distribution)


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.017 ms/op
Iteration   1: 3.860 ±(99.9%) 0.019 ms/op
Iteration   2: 3.809 ±(99.9%) 0.032 ms/op
Iteration   3: 3.906 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.858 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (3.809, 3.858, 3.906), stdev = 0.049
  CI (99.9%): [2.971, 4.745] (assumes normal distribution)


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.007 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.313 ms/op
                 createUser·p0.9999: 15.830 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 2.998 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  8.561 ms/op
                 createUser·p0.9999: 22.391 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.567 ms/op
                 createUser·p0.999:  8.121 ms/op
                 createUser·p0.9999: 19.484 ms/op
                 createUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320688
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28084 
    [ 2.500,  5.000) = 290447 
    [ 5.000,  7.500) = 1644 
    [ 7.500, 10.000) = 276 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      8.249 ms/op
     p(99.9900) =     20.017 ms/op
     p(99.9990) =     23.390 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.863 ±(99.9%) 0.006 ms/op
Iteration   1: 2.925 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.597 ms/op
                 existUser·p0.9999: 11.403 ms/op
                 existUser·p1.00:   11.616 ms/op

Iteration   2: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.617 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.913 ms/op
                 existUser·p0.9999: 12.158 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   3: 2.895 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.479 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  8.121 ms/op
                 existUser·p0.9999: 16.743 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329578
  mean =      2.912 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3123 
    [ 1.250,  2.500) = 43690 
    [ 2.500,  3.750) = 269083 
    [ 3.750,  5.000) = 11974 
    [ 5.000,  6.250) = 674 
    [ 6.250,  7.500) = 524 
    [ 7.500,  8.750) = 242 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      8.171 ms/op
     p(99.9900) =     14.910 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.845 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 2.973 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  8.822 ms/op
                 getUser·p0.9999: 20.881 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.774 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.554 ms/op
                 getUser·p0.9999: 16.684 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   3: 2.951 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.252 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.121 ms/op
                 getUser·p0.9999: 17.011 ms/op
                 getUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323027
  mean =      2.973 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30182 
    [ 2.500,  5.000) = 290988 
    [ 5.000,  7.500) = 1442 
    [ 7.500, 10.000) = 217 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.252 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.061 ms/op
     p(99.9900) =     19.316 ms/op
     p(99.9990) =     21.095 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 5.146 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.010 ms/op
Iteration   1: 3.891 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.764 ms/op
                 listUser·p0.999:  11.944 ms/op
                 listUser·p0.9999: 14.944 ms/op
                 listUser·p1.00:   15.516 ms/op

Iteration   2: 3.866 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  16.713 ms/op
                 listUser·p0.9999: 27.066 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   3: 3.897 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.684 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  17.366 ms/op
                 listUser·p0.9999: 23.711 ms/op
                 listUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246987
  mean =      3.885 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5763 
    [ 2.500,  5.000) = 219175 
    [ 5.000,  7.500) = 20634 
    [ 7.500, 10.000) = 804 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     15.369 ms/op
     p(99.9900) =     26.650 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.668 ± 0.932  ops/ms
ClientGrpc.existUser                       thrpt       3  11.375 ± 1.233  ops/ms
ClientGrpc.getUser                         thrpt       3  10.803 ± 2.081  ops/ms
ClientGrpc.listUser                        thrpt       3   8.206 ± 0.635  ops/ms
ClientGrpc.createUser                       avgt       3   2.983 ± 0.610   ms/op
ClientGrpc.existUser                        avgt       3   2.948 ± 0.366   ms/op
ClientGrpc.getUser                          avgt       3   2.985 ± 0.426   ms/op
ClientGrpc.listUser                         avgt       3   3.858 ± 0.887   ms/op
ClientGrpc.createUser                     sample  320688   2.992 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.524           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.249           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.017           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.560           ms/op
ClientGrpc.existUser                      sample  329578   2.912 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.479           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.171           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.910           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.974           ms/op
ClientGrpc.getUser                        sample  323027   2.973 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.252           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.061           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.316           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.168           ms/op
ClientGrpc.listUser                       sample  246987   3.885 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.684           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.369           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.650           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.394           ms/op
