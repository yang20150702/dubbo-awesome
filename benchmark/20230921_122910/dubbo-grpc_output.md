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
# Warmup Iteration   1: 2.092 ops/ms
# Warmup Iteration   2: 4.941 ops/ms
# Warmup Iteration   3: 6.594 ops/ms
Iteration   1: 6.844 ops/ms
Iteration   2: 6.762 ops/ms
Iteration   3: 7.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.877 ±(99.9%) 2.469 ops/ms [Average]
  (min, avg, max) = (6.762, 6.877, 7.026), stdev = 0.135
  CI (99.9%): [4.408, 9.346] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.341 ops/ms
# Warmup Iteration   2: 6.694 ops/ms
# Warmup Iteration   3: 7.447 ops/ms
Iteration   1: 7.383 ops/ms
Iteration   2: 7.478 ops/ms
Iteration   3: 7.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.488 ±(99.9%) 2.006 ops/ms [Average]
  (min, avg, max) = (7.383, 7.488, 7.603), stdev = 0.110
  CI (99.9%): [5.482, 9.494] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.776 ops/ms
# Warmup Iteration   2: 6.441 ops/ms
# Warmup Iteration   3: 6.755 ops/ms
Iteration   1: 6.980 ops/ms
Iteration   2: 6.662 ops/ms
Iteration   3: 6.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.829 ±(99.9%) 2.904 ops/ms [Average]
  (min, avg, max) = (6.662, 6.829, 6.980), stdev = 0.159
  CI (99.9%): [3.925, 9.733] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.550 ops/ms
# Warmup Iteration   2: 4.693 ops/ms
# Warmup Iteration   3: 5.337 ops/ms
Iteration   1: 5.519 ops/ms
Iteration   2: 5.367 ops/ms
Iteration   3: 5.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.414 ±(99.9%) 1.674 ops/ms [Average]
  (min, avg, max) = (5.354, 5.414, 5.519), stdev = 0.092
  CI (99.9%): [3.739, 7.088] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.799 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.007 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.727 ±(99.9%) 0.004 ms/op
Iteration   1: 4.761 ±(99.9%) 0.004 ms/op
Iteration   2: 4.523 ±(99.9%) 0.004 ms/op
Iteration   3: 4.559 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.614 ±(99.9%) 2.337 ms/op [Average]
  (min, avg, max) = (4.523, 4.614, 4.761), stdev = 0.128
  CI (99.9%): [2.277, 6.952] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.902 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.594 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.384 ±(99.9%) 0.004 ms/op
Iteration   1: 4.212 ±(99.9%) 0.004 ms/op
Iteration   2: 4.180 ±(99.9%) 0.005 ms/op
Iteration   3: 4.230 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.207 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (4.180, 4.207, 4.230), stdev = 0.025
  CI (99.9%): [3.748, 4.667] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.328 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.933 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.661 ±(99.9%) 0.005 ms/op
Iteration   1: 4.539 ±(99.9%) 0.004 ms/op
Iteration   2: 4.527 ±(99.9%) 0.005 ms/op
Iteration   3: 4.576 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.547 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (4.527, 4.547, 4.576), stdev = 0.025
  CI (99.9%): [4.086, 5.008] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.165 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 6.629 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.951 ±(99.9%) 0.015 ms/op
Iteration   1: 5.880 ±(99.9%) 0.027 ms/op
Iteration   2: 5.779 ±(99.9%) 0.028 ms/op
Iteration   3: 5.776 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.812 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (5.776, 5.812, 5.880), stdev = 0.059
  CI (99.9%): [4.731, 6.892] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.445 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.057 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.585 ±(99.9%) 0.014 ms/op
Iteration   1: 4.652 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   4.481 ms/op
                 createUser·p0.90:   5.841 ms/op
                 createUser·p0.95:   6.439 ms/op
                 createUser·p0.99:   8.962 ms/op
                 createUser·p0.999:  15.854 ms/op
                 createUser·p0.9999: 22.479 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   2: 4.588 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   4.440 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   6.152 ms/op
                 createUser·p0.99:   8.307 ms/op
                 createUser·p0.999:  11.521 ms/op
                 createUser·p0.9999: 25.135 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   3: 4.621 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.425 ms/op
                 createUser·p0.50:   4.456 ms/op
                 createUser·p0.90:   5.825 ms/op
                 createUser·p0.95:   6.316 ms/op
                 createUser·p0.99:   8.929 ms/op
                 createUser·p0.999:  17.817 ms/op
                 createUser·p0.9999: 40.840 ms/op
                 createUser·p1.00:   41.157 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 207667
  mean =      4.620 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 149766 
    [ 5.000, 10.000) = 56864 
    [10.000, 15.000) = 839 
    [15.000, 20.000) = 62 
    [20.000, 25.000) = 82 
    [25.000, 30.000) = 22 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.784 ms/op
     p(95.0000) =      6.300 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     14.735 ms/op
     p(99.9900) =     40.335 ms/op
     p(99.9990) =     41.091 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.548 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.647 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.458 ±(99.9%) 0.013 ms/op
Iteration   1: 4.268 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.399 ms/op
                 existUser·p0.95:   5.964 ms/op
                 existUser·p0.99:   8.167 ms/op
                 existUser·p0.999:  12.092 ms/op
                 existUser·p0.9999: 17.564 ms/op
                 existUser·p1.00:   18.285 ms/op

Iteration   2: 4.119 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.020 ms/op
                 existUser·p0.50:   4.022 ms/op
                 existUser·p0.90:   5.079 ms/op
                 existUser·p0.95:   5.616 ms/op
                 existUser·p0.99:   8.176 ms/op
                 existUser·p0.999:  12.032 ms/op
                 existUser·p0.9999: 20.029 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   3: 4.304 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   4.174 ms/op
                 existUser·p0.90:   5.399 ms/op
                 existUser·p0.95:   5.980 ms/op
                 existUser·p0.99:   8.118 ms/op
                 existUser·p0.999:  13.560 ms/op
                 existUser·p0.9999: 20.859 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 226966
  mean =      4.229 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8556 
    [ 2.500,  5.000) = 184282 
    [ 5.000,  7.500) = 30817 
    [ 7.500, 10.000) = 2522 
    [10.000, 12.500) = 560 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     12.502 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.399 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.153 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.484 ±(99.9%) 0.014 ms/op
Iteration   1: 4.480 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.595 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  15.172 ms/op
                 getUser·p0.9999: 33.087 ms/op
                 getUser·p1.00:   33.817 ms/op

Iteration   2: 4.400 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.543 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  14.413 ms/op
                 getUser·p0.9999: 26.238 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   3: 4.454 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   8.405 ms/op
                 getUser·p0.999:  12.032 ms/op
                 getUser·p0.9999: 23.090 ms/op
                 getUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215988
  mean =      4.444 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4725 
    [ 2.500,  5.000) = 170778 
    [ 5.000,  7.500) = 36441 
    [ 7.500, 10.000) = 3073 
    [10.000, 12.500) = 630 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     14.140 ms/op
     p(99.9900) =     31.359 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.723 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 6.090 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.785 ±(99.9%) 0.021 ms/op
Iteration   1: 5.675 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.635 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.223 ms/op
                 listUser·p0.999:  20.382 ms/op
                 listUser·p0.9999: 23.935 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 5.902 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.704 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   8.110 ms/op
                 listUser·p0.95:   9.208 ms/op
                 listUser·p0.99:   12.681 ms/op
                 listUser·p0.999:  23.884 ms/op
                 listUser·p0.9999: 34.286 ms/op
                 listUser·p1.00:   34.800 ms/op

Iteration   3: 5.973 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   8.192 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   11.764 ms/op
                 listUser·p0.999:  27.886 ms/op
                 listUser·p0.9999: 35.909 ms/op
                 listUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 164182
  mean =      5.847 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 157 
    [ 2.500,  5.000) = 52305 
    [ 5.000,  7.500) = 90076 
    [ 7.500, 10.000) = 17075 
    [10.000, 12.500) = 3307 
    [12.500, 15.000) = 726 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      7.963 ms/op
     p(95.0000) =      9.060 ms/op
     p(99.0000) =     11.878 ms/op
     p(99.9000) =     24.177 ms/op
     p(99.9900) =     34.417 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.877 ± 2.469  ops/ms
ClientGrpc.existUser                       thrpt       3   7.488 ± 2.006  ops/ms
ClientGrpc.getUser                         thrpt       3   6.829 ± 2.904  ops/ms
ClientGrpc.listUser                        thrpt       3   5.414 ± 1.674  ops/ms
ClientGrpc.createUser                       avgt       3   4.614 ± 2.337   ms/op
ClientGrpc.existUser                        avgt       3   4.207 ± 0.460   ms/op
ClientGrpc.getUser                          avgt       3   4.547 ± 0.461   ms/op
ClientGrpc.listUser                         avgt       3   5.812 ± 1.081   ms/op
ClientGrpc.createUser                     sample  207667   4.620 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.425           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.784           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.300           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.749           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.735           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          40.335           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          41.157           ms/op
ClientGrpc.existUser                      sample  226966   4.229 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.854           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.308           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.865           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.143           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.502           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.414           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.070           ms/op
ClientGrpc.getUser                        sample  215988   4.444 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.543           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.480           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.038           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.585           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.140           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.359           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.817           ms/op
ClientGrpc.listUser                       sample  164182   5.847 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.495           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.963           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.060           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.878           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          24.177           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.417           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.438           ms/op
