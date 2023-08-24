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
# Warmup Iteration   1: 3.106 ops/ms
# Warmup Iteration   2: 6.832 ops/ms
# Warmup Iteration   3: 8.096 ops/ms
Iteration   1: 8.384 ops/ms
Iteration   2: 8.742 ops/ms
Iteration   3: 8.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.501 ±(99.9%) 3.814 ops/ms [Average]
  (min, avg, max) = (8.376, 8.501, 8.742), stdev = 0.209
  CI (99.9%): [4.687, 12.315] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.532 ops/ms
# Warmup Iteration   2: 8.417 ops/ms
# Warmup Iteration   3: 9.136 ops/ms
Iteration   1: 9.097 ops/ms
Iteration   2: 9.148 ops/ms
Iteration   3: 9.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.137 ±(99.9%) 0.665 ops/ms [Average]
  (min, avg, max) = (9.097, 9.137, 9.167), stdev = 0.036
  CI (99.9%): [8.472, 9.802] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.567 ops/ms
# Warmup Iteration   2: 8.348 ops/ms
# Warmup Iteration   3: 8.528 ops/ms
Iteration   1: 8.593 ops/ms
Iteration   2: 8.425 ops/ms
Iteration   3: 8.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.603 ±(99.9%) 3.342 ops/ms [Average]
  (min, avg, max) = (8.425, 8.603, 8.791), stdev = 0.183
  CI (99.9%): [5.261, 11.945] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.503 ops/ms
# Warmup Iteration   2: 6.231 ops/ms
# Warmup Iteration   3: 6.485 ops/ms
Iteration   1: 6.500 ops/ms
Iteration   2: 6.688 ops/ms
Iteration   3: 6.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.633 ±(99.9%) 2.111 ops/ms [Average]
  (min, avg, max) = (6.500, 6.633, 6.710), stdev = 0.116
  CI (99.9%): [4.522, 8.743] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.331 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.007 ms/op
Iteration   1: 3.842 ±(99.9%) 0.003 ms/op
Iteration   2: 3.690 ±(99.9%) 0.003 ms/op
Iteration   3: 3.673 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.735 ±(99.9%) 1.703 ms/op [Average]
  (min, avg, max) = (3.673, 3.735, 3.842), stdev = 0.093
  CI (99.9%): [2.032, 5.438] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.847 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.003 ms/op
Iteration   1: 3.501 ±(99.9%) 0.003 ms/op
Iteration   2: 3.601 ±(99.9%) 0.003 ms/op
Iteration   3: 3.500 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.534 ±(99.9%) 1.061 ms/op [Average]
  (min, avg, max) = (3.500, 3.534, 3.601), stdev = 0.058
  CI (99.9%): [2.474, 4.595] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.961 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.005 ms/op
Iteration   1: 3.773 ±(99.9%) 0.010 ms/op
Iteration   2: 3.665 ±(99.9%) 0.003 ms/op
Iteration   3: 3.613 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.684 ±(99.9%) 1.494 ms/op [Average]
  (min, avg, max) = (3.613, 3.684, 3.773), stdev = 0.082
  CI (99.9%): [2.189, 5.178] (assumes normal distribution)


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
# Warmup Iteration   1: 6.736 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.130 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.740 ±(99.9%) 0.012 ms/op
Iteration   1: 4.831 ±(99.9%) 0.019 ms/op
Iteration   2: 4.662 ±(99.9%) 0.014 ms/op
Iteration   3: 4.787 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.760 ±(99.9%) 1.606 ms/op [Average]
  (min, avg, max) = (4.662, 4.760, 4.831), stdev = 0.088
  CI (99.9%): [3.155, 6.366] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.454 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.010 ms/op
Iteration   1: 3.739 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  9.731 ms/op
                 createUser·p0.9999: 16.938 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 3.631 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  11.548 ms/op
                 createUser·p0.9999: 17.596 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   3: 3.638 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  12.291 ms/op
                 createUser·p0.9999: 19.300 ms/op
                 createUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261531
  mean =      3.668 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 182 
    [ 1.250,  2.500) = 10422 
    [ 2.500,  3.750) = 151339 
    [ 3.750,  5.000) = 89825 
    [ 5.000,  6.250) = 7222 
    [ 6.250,  7.500) = 1249 
    [ 7.500,  8.750) = 581 
    [ 8.750, 10.000) = 288 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 81 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     19.822 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 4.865 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.008 ms/op
Iteration   1: 3.410 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  9.586 ms/op
                 existUser·p0.9999: 14.661 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   2: 3.496 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  7.848 ms/op
                 existUser·p0.9999: 19.356 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   3: 3.488 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 30.600 ms/op
                 existUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277105
  mean =      3.464 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13323 
    [ 2.500,  5.000) = 257913 
    [ 5.000,  7.500) = 5149 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.567 ms/op
     p(99.9900) =     29.421 ms/op
     p(99.9990) =     30.850 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


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
# Warmup Iteration   1: 5.175 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.010 ms/op
Iteration   1: 3.791 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.361 ms/op
                 getUser·p0.999:  13.085 ms/op
                 getUser·p0.9999: 14.352 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 3.708 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  14.091 ms/op
                 getUser·p0.9999: 24.216 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   3: 3.738 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  10.928 ms/op
                 getUser·p0.9999: 19.787 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256351
  mean =      3.745 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5183 
    [ 2.500,  5.000) = 242232 
    [ 5.000,  7.500) = 7665 
    [ 7.500, 10.000) = 910 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     11.316 ms/op
     p(99.9900) =     23.879 ms/op
     p(99.9990) =     24.412 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 6.678 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.059 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.818 ±(99.9%) 0.015 ms/op
Iteration   1: 4.813 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.029 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  18.514 ms/op
                 listUser·p0.9999: 23.462 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   2: 4.690 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  16.564 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   3: 4.868 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.439 ms/op
                 listUser·p0.95:   7.274 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  19.605 ms/op
                 listUser·p0.9999: 29.431 ms/op
                 listUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200331
  mean =      4.789 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 263 
    [ 2.500,  5.000) = 151216 
    [ 5.000,  7.500) = 42572 
    [ 7.500, 10.000) = 5318 
    [10.000, 12.500) = 425 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      6.038 ms/op
     p(95.0000) =      7.012 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     28.670 ms/op
     p(99.9990) =     30.571 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.501 ± 3.814  ops/ms
ClientGrpc.existUser                       thrpt       3   9.137 ± 0.665  ops/ms
ClientGrpc.getUser                         thrpt       3   8.603 ± 3.342  ops/ms
ClientGrpc.listUser                        thrpt       3   6.633 ± 2.111  ops/ms
ClientGrpc.createUser                       avgt       3   3.735 ± 1.703   ms/op
ClientGrpc.existUser                        avgt       3   3.534 ± 1.061   ms/op
ClientGrpc.getUser                          avgt       3   3.684 ± 1.494   ms/op
ClientGrpc.listUser                         avgt       3   4.760 ± 1.606   ms/op
ClientGrpc.createUser                     sample  261531   3.668 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.807           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.210           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.911           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.924           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.956           ms/op
ClientGrpc.existUser                      sample  277105   3.464 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.786           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.644           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.567           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.421           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.966           ms/op
ClientGrpc.getUser                        sample  256351   3.745 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.959           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.283           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.316           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.879           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.478           ms/op
ClientGrpc.listUser                       sample  200331   4.789 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.888           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.847           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.826           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.670           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.671           ms/op
