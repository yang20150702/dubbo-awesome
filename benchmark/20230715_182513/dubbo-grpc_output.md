# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.263 ops/ms
# Warmup Iteration   2: 7.271 ops/ms
# Warmup Iteration   3: 9.853 ops/ms
Iteration   1: 10.777 ops/ms
Iteration   2: 11.033 ops/ms
Iteration   3: 10.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.909 ±(99.9%) 2.342 ops/ms [Average]
  (min, avg, max) = (10.777, 10.909, 11.033), stdev = 0.128
  CI (99.9%): [8.567, 13.252] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 6.908 ops/ms
# Warmup Iteration   2: 10.227 ops/ms
# Warmup Iteration   3: 11.573 ops/ms
Iteration   1: 11.980 ops/ms
Iteration   2: 11.816 ops/ms
Iteration   3: 11.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.746 ±(99.9%) 5.039 ops/ms [Average]
  (min, avg, max) = (11.441, 11.746, 11.980), stdev = 0.276
  CI (99.9%): [6.707, 16.784] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 6.416 ops/ms
# Warmup Iteration   2: 9.697 ops/ms
# Warmup Iteration   3: 10.688 ops/ms
Iteration   1: 10.854 ops/ms
Iteration   2: 11.423 ops/ms
Iteration   3: 11.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  11.118 ±(99.9%) 5.233 ops/ms [Average]
  (min, avg, max) = (10.854, 11.118, 11.423), stdev = 0.287
  CI (99.9%): [5.884, 16.351] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 5.948 ops/ms
# Warmup Iteration   2: 8.401 ops/ms
# Warmup Iteration   3: 8.623 ops/ms
Iteration   1: 8.369 ops/ms
Iteration   2: 8.403 ops/ms
Iteration   3: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.376 ±(99.9%) 0.426 ops/ms [Average]
  (min, avg, max) = (8.358, 8.376, 8.403), stdev = 0.023
  CI (99.9%): [7.951, 8.802] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 4.735 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.008 ms/op
Iteration   1: 2.897 ±(99.9%) 0.009 ms/op
Iteration   2: 2.895 ±(99.9%) 0.007 ms/op
Iteration   3: 2.960 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.917 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (2.895, 2.917, 2.960), stdev = 0.037
  CI (99.9%): [2.247, 3.588] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.153 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.832 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.661 ±(99.9%) 0.007 ms/op
Iteration   1: 2.621 ±(99.9%) 0.007 ms/op
Iteration   2: 2.589 ±(99.9%) 0.009 ms/op
Iteration   3: 2.591 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.600 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.589, 2.600, 2.621), stdev = 0.018
  CI (99.9%): [2.276, 2.924] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.747 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.819 ±(99.9%) 0.007 ms/op
Iteration   1: 2.787 ±(99.9%) 0.007 ms/op
Iteration   2: 2.758 ±(99.9%) 0.007 ms/op
Iteration   3: 2.774 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.773 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.758, 2.773, 2.787), stdev = 0.015
  CI (99.9%): [2.503, 3.043] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.563 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.010 ms/op
Iteration   1: 3.488 ±(99.9%) 0.013 ms/op
Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
Iteration   3: 3.496 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.486 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (3.473, 3.486, 3.496), stdev = 0.012
  CI (99.9%): [3.272, 3.699] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.780 ±(99.9%) 0.006 ms/op
Iteration   1: 2.725 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  11.003 ms/op
                 createUser·p0.9999: 21.176 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   2: 2.766 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   2.716 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.016 ms/op
                 createUser·p0.9999: 18.266 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   3: 2.732 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  9.339 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 350371
  mean =      2.741 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115585 
    [ 2.500,  5.000) = 233264 
    [ 5.000,  7.500) = 980 
    [ 7.500, 10.000) = 247 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      2.683 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      9.382 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 3.420 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.855 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.635 ±(99.9%) 0.006 ms/op
Iteration   1: 2.593 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.135 ms/op
                 existUser·p0.999:  6.865 ms/op
                 existUser·p0.9999: 18.109 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   2: 2.643 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  9.653 ms/op
                 existUser·p0.9999: 15.857 ms/op
                 existUser·p1.00:   16.171 ms/op

Iteration   3: 2.606 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  5.569 ms/op
                 existUser·p0.9999: 22.774 ms/op
                 existUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 367098
  mean =      2.614 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 159395 
    [ 2.500,  5.000) = 206525 
    [ 5.000,  7.500) = 791 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.236 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      7.733 ms/op
     p(99.9900) =     20.092 ms/op
     p(99.9990) =     23.013 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.829 ±(99.9%) 0.007 ms/op
Iteration   1: 2.760 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   2.707 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.827 ms/op
                 getUser·p0.9999: 16.856 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   2: 2.763 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   2.703 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.478 ms/op
                 getUser·p0.9999: 21.314 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   3: 2.755 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   2.695 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  10.437 ms/op
                 getUser·p0.9999: 15.768 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 347743
  mean =      2.759 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 111794 
    [ 2.500,  5.000) = 234292 
    [ 5.000,  7.500) = 1122 
    [ 7.500, 10.000) = 204 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.703 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.745 ms/op
     p(99.9900) =     17.175 ms/op
     p(99.9990) =     21.645 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.278 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.013 ms/op
Iteration   1: 3.535 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.301 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.030 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   2: 3.515 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.301 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.814 ms/op
                 listUser·p0.9999: 21.984 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   3: 3.453 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.256 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.510 ms/op
                 listUser·p0.9999: 21.323 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 274251
  mean =      3.500 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26517 
    [ 2.500,  5.000) = 223785 
    [ 5.000,  7.500) = 22704 
    [ 7.500, 10.000) = 760 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     13.877 ms/op
     p(99.9900) =     21.449 ms/op
     p(99.9990) =     22.242 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.909 ± 2.342  ops/ms
ClientGrpc.existUser                       thrpt       3  11.746 ± 5.039  ops/ms
ClientGrpc.getUser                         thrpt       3  11.118 ± 5.233  ops/ms
ClientGrpc.listUser                        thrpt       3   8.376 ± 0.426  ops/ms
ClientGrpc.createUser                       avgt       3   2.917 ± 0.671   ms/op
ClientGrpc.existUser                        avgt       3   2.600 ± 0.324   ms/op
ClientGrpc.getUser                          avgt       3   2.773 ± 0.270   ms/op
ClientGrpc.listUser                         avgt       3   3.486 ± 0.213   ms/op
ClientGrpc.createUser                     sample  350371   2.741 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.790           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.683           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.351           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.382           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.496           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.707           ms/op
ClientGrpc.existUser                      sample  367098   2.614 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.556           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.572           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.236           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.733           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.092           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.233           ms/op
ClientGrpc.getUser                        sample  347743   2.759 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.655           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.703           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.404           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.745           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.175           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.413           ms/op
ClientGrpc.listUser                       sample  274251   3.500 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.061           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.285           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.877           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.449           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.101           ms/op
