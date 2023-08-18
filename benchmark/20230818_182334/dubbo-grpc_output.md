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
# Warmup Iteration   1: 2.999 ops/ms
# Warmup Iteration   2: 7.291 ops/ms
# Warmup Iteration   3: 7.867 ops/ms
Iteration   1: 7.955 ops/ms
Iteration   2: 8.200 ops/ms
Iteration   3: 7.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.029 ±(99.9%) 2.716 ops/ms [Average]
  (min, avg, max) = (7.932, 8.029, 8.200), stdev = 0.149
  CI (99.9%): [5.313, 10.745] (assumes normal distribution)


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
# Warmup Iteration   1: 6.177 ops/ms
# Warmup Iteration   2: 8.993 ops/ms
# Warmup Iteration   3: 9.040 ops/ms
Iteration   1: 9.356 ops/ms
Iteration   2: 9.791 ops/ms
Iteration   3: 9.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.458 ±(99.9%) 5.390 ops/ms [Average]
  (min, avg, max) = (9.227, 9.458, 9.791), stdev = 0.295
  CI (99.9%): [4.067, 14.848] (assumes normal distribution)


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
# Warmup Iteration   1: 5.035 ops/ms
# Warmup Iteration   2: 7.752 ops/ms
# Warmup Iteration   3: 8.077 ops/ms
Iteration   1: 7.978 ops/ms
Iteration   2: 8.317 ops/ms
Iteration   3: 8.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.367 ±(99.9%) 7.602 ops/ms [Average]
  (min, avg, max) = (7.978, 8.367, 8.807), stdev = 0.417
  CI (99.9%): [0.765, 15.970] (assumes normal distribution)


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
# Warmup Iteration   1: 4.774 ops/ms
# Warmup Iteration   2: 6.018 ops/ms
# Warmup Iteration   3: 6.406 ops/ms
Iteration   1: 6.651 ops/ms
Iteration   2: 6.413 ops/ms
Iteration   3: 6.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.406 ±(99.9%) 4.535 ops/ms [Average]
  (min, avg, max) = (6.154, 6.406, 6.651), stdev = 0.249
  CI (99.9%): [1.870, 10.941] (assumes normal distribution)


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
# Warmup Iteration   1: 5.524 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.186 ±(99.9%) 0.004 ms/op
Iteration   1: 3.942 ±(99.9%) 0.003 ms/op
Iteration   2: 3.880 ±(99.9%) 0.002 ms/op
Iteration   3: 3.916 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.912 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (3.880, 3.912, 3.942), stdev = 0.031
  CI (99.9%): [3.345, 4.479] (assumes normal distribution)


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
# Warmup Iteration   1: 5.120 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.002 ms/op
Iteration   1: 3.545 ±(99.9%) 0.002 ms/op
Iteration   2: 3.604 ±(99.9%) 0.003 ms/op
Iteration   3: 3.532 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.560 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (3.532, 3.560, 3.604), stdev = 0.038
  CI (99.9%): [2.861, 4.259] (assumes normal distribution)


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
# Warmup Iteration   1: 5.867 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.002 ms/op
Iteration   1: 3.843 ±(99.9%) 0.002 ms/op
Iteration   2: 3.773 ±(99.9%) 0.004 ms/op
Iteration   3: 3.767 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.794 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (3.767, 3.794, 3.843), stdev = 0.043
  CI (99.9%): [3.017, 4.572] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.462 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.280 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.926 ±(99.9%) 0.014 ms/op
Iteration   1: 5.042 ±(99.9%) 0.026 ms/op
Iteration   2: 5.090 ±(99.9%) 0.026 ms/op
Iteration   3: 4.856 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.996 ±(99.9%) 2.255 ms/op [Average]
  (min, avg, max) = (4.856, 4.996, 5.090), stdev = 0.124
  CI (99.9%): [2.741, 7.251] (assumes normal distribution)


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
# Warmup Iteration   1: 5.383 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.010 ms/op
Iteration   1: 3.782 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  11.530 ms/op
                 createUser·p0.9999: 17.793 ms/op
                 createUser·p1.00:   19.235 ms/op

Iteration   2: 3.881 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  14.083 ms/op
                 createUser·p0.9999: 18.940 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   3: 3.913 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   6.758 ms/op
                 createUser·p0.999:  12.380 ms/op
                 createUser·p0.9999: 25.422 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 248919
  mean =      3.858 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6663 
    [ 2.500,  5.000) = 224318 
    [ 5.000,  7.500) = 16465 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     24.350 ms/op
     p(99.9990) =     26.559 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 5.287 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.010 ms/op
Iteration   1: 3.656 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  11.321 ms/op
                 existUser·p0.9999: 15.048 ms/op
                 existUser·p1.00:   15.811 ms/op

Iteration   2: 3.688 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  11.394 ms/op
                 existUser·p0.9999: 25.089 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 3.742 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  9.624 ms/op
                 existUser·p0.9999: 24.542 ms/op
                 existUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 259924
  mean =      3.695 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7266 
    [ 2.500,  5.000) = 240773 
    [ 5.000,  7.500) = 10821 
    [ 7.500, 10.000) = 726 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     10.813 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     25.218 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 5.543 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.362 ±(99.9%) 0.013 ms/op
Iteration   1: 4.468 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.119 ms/op
                 getUser·p0.99:   8.137 ms/op
                 getUser·p0.999:  14.329 ms/op
                 getUser·p0.9999: 20.208 ms/op
                 getUser·p1.00:   22.184 ms/op

Iteration   2: 4.264 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.284 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   7.099 ms/op
                 getUser·p0.999:  12.485 ms/op
                 getUser·p0.9999: 20.218 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   3: 4.239 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   4.157 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  11.568 ms/op
                 getUser·p0.9999: 22.577 ms/op
                 getUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 222092
  mean =      4.321 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5943 
    [ 2.500,  5.000) = 179412 
    [ 5.000,  7.500) = 34709 
    [ 7.500, 10.000) = 1464 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     12.501 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 8.330 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.186 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.574 ±(99.9%) 0.021 ms/op
Iteration   1: 5.555 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.972 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   7.389 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   10.600 ms/op
                 listUser·p0.999:  16.904 ms/op
                 listUser·p0.9999: 23.559 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   2: 5.638 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.833 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.447 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.945 ms/op
                 listUser·p0.999:  21.325 ms/op
                 listUser·p0.9999: 26.771 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   3: 5.554 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   8.154 ms/op
                 listUser·p0.99:   10.441 ms/op
                 listUser·p0.999:  27.525 ms/op
                 listUser·p0.9999: 30.973 ms/op
                 listUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171977
  mean =      5.582 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 101 
    [ 2.500,  5.000) = 65584 
    [ 5.000,  7.500) = 90767 
    [ 7.500, 10.000) = 12891 
    [10.000, 12.500) = 1944 
    [12.500, 15.000) = 312 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      7.356 ms/op
     p(95.0000) =      8.339 ms/op
     p(99.0000) =     10.666 ms/op
     p(99.9000) =     21.136 ms/op
     p(99.9900) =     30.238 ms/op
     p(99.9990) =     31.288 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.029 ± 2.716  ops/ms
ClientGrpc.existUser                       thrpt       3   9.458 ± 5.390  ops/ms
ClientGrpc.getUser                         thrpt       3   8.367 ± 7.602  ops/ms
ClientGrpc.listUser                        thrpt       3   6.406 ± 4.535  ops/ms
ClientGrpc.createUser                       avgt       3   3.912 ± 0.567   ms/op
ClientGrpc.existUser                        avgt       3   3.560 ± 0.699   ms/op
ClientGrpc.getUser                          avgt       3   3.794 ± 0.777   ms/op
ClientGrpc.listUser                         avgt       3   4.996 ± 2.255   ms/op
ClientGrpc.createUser                     sample  248919   3.858 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.870           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.792           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.235           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.611           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.927           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.350           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.575           ms/op
ClientGrpc.existUser                      sample  259924   3.695 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.839           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.579           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.956           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.029           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.813           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.707           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.330           ms/op
ClientGrpc.getUser                        sample  222092   4.321 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.942           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.366           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.857           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.365           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.501           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.151           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.708           ms/op
ClientGrpc.listUser                       sample  171977   5.582 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.341           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.259           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.356           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.339           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.666           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.136           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.238           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.359           ms/op
