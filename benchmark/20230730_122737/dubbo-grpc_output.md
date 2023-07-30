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
# Warmup Iteration   1: 4.264 ops/ms
# Warmup Iteration   2: 8.918 ops/ms
# Warmup Iteration   3: 10.119 ops/ms
Iteration   1: 10.472 ops/ms
Iteration   2: 10.522 ops/ms
Iteration   3: 10.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.550 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (10.472, 10.550, 10.657), stdev = 0.096
  CI (99.9%): [8.803, 12.298] (assumes normal distribution)


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
# Warmup Iteration   1: 7.149 ops/ms
# Warmup Iteration   2: 10.437 ops/ms
# Warmup Iteration   3: 11.103 ops/ms
Iteration   1: 10.430 ops/ms
Iteration   2: 10.647 ops/ms
Iteration   3: 10.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.671 ±(99.9%) 4.645 ops/ms [Average]
  (min, avg, max) = (10.430, 10.671, 10.937), stdev = 0.255
  CI (99.9%): [6.027, 15.316] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.287 ops/ms
# Warmup Iteration   2: 9.783 ops/ms
# Warmup Iteration   3: 10.299 ops/ms
Iteration   1: 10.207 ops/ms
Iteration   2: 10.367 ops/ms
Iteration   3: 10.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.319 ±(99.9%) 1.772 ops/ms [Average]
  (min, avg, max) = (10.207, 10.319, 10.383), stdev = 0.097
  CI (99.9%): [8.547, 12.091] (assumes normal distribution)


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
# Warmup Iteration   1: 5.835 ops/ms
# Warmup Iteration   2: 7.227 ops/ms
# Warmup Iteration   3: 7.679 ops/ms
Iteration   1: 7.682 ops/ms
Iteration   2: 7.757 ops/ms
Iteration   3: 7.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.777 ±(99.9%) 1.936 ops/ms [Average]
  (min, avg, max) = (7.682, 7.777, 7.892), stdev = 0.106
  CI (99.9%): [5.841, 9.713] (assumes normal distribution)


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.002 ms/op
Iteration   1: 3.075 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.004 ms/op
Iteration   3: 3.037 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.047 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (3.027, 3.047, 3.075), stdev = 0.025
  CI (99.9%): [2.583, 3.511] (assumes normal distribution)


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.002 ms/op
Iteration   1: 3.000 ±(99.9%) 0.001 ms/op
Iteration   2: 2.894 ±(99.9%) 0.001 ms/op
Iteration   3: 2.906 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.933 ±(99.9%) 1.059 ms/op [Average]
  (min, avg, max) = (2.894, 2.933, 3.000), stdev = 0.058
  CI (99.9%): [1.874, 3.992] (assumes normal distribution)


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.003 ms/op
Iteration   1: 3.050 ±(99.9%) 0.003 ms/op
Iteration   2: 3.034 ±(99.9%) 0.003 ms/op
Iteration   3: 3.046 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.044 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (3.034, 3.044, 3.050), stdev = 0.008
  CI (99.9%): [2.893, 3.194] (assumes normal distribution)


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
# Warmup Iteration   1: 5.178 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.027 ms/op
Iteration   1: 4.046 ±(99.9%) 0.020 ms/op
Iteration   2: 4.073 ±(99.9%) 0.014 ms/op
Iteration   3: 4.025 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.048 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (4.025, 4.048, 4.073), stdev = 0.024
  CI (99.9%): [3.608, 4.487] (assumes normal distribution)


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  6.963 ms/op
                 createUser·p0.9999: 13.497 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 15.600 ms/op
                 createUser·p1.00:   16.138 ms/op

Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.961 ms/op
                 createUser·p0.9999: 17.302 ms/op
                 createUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315317
  mean =      3.043 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 725 
    [ 1.250,  2.500) = 22982 
    [ 2.500,  3.750) = 270994 
    [ 3.750,  5.000) = 18904 
    [ 5.000,  6.250) = 939 
    [ 6.250,  7.500) = 297 
    [ 7.500,  8.750) = 176 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     16.277 ms/op
     p(99.9990) =     18.184 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.962 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 19.628 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   2: 2.934 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.507 ms/op
                 existUser·p0.9999: 15.698 ms/op
                 existUser·p1.00:   16.105 ms/op

Iteration   3: 2.937 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  6.906 ms/op
                 existUser·p0.9999: 16.912 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326165
  mean =      2.944 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31351 
    [ 2.500,  5.000) = 293572 
    [ 5.000,  7.500) = 938 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.257 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     20.594 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 4.239 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.008 ms/op
Iteration   1: 3.069 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  11.807 ms/op
                 getUser·p0.9999: 20.840 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  12.255 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  6.678 ms/op
                 getUser·p0.9999: 22.870 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313439
  mean =      3.061 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20460 
    [ 2.500,  5.000) = 291336 
    [ 5.000,  7.500) = 1089 
    [ 7.500, 10.000) = 266 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      9.135 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     24.502 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 5.603 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.010 ms/op
Iteration   1: 4.048 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  14.872 ms/op
                 listUser·p0.9999: 19.565 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   2: 3.971 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.777 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.858 ms/op
                 listUser·p0.999:  18.396 ms/op
                 listUser·p0.9999: 31.781 ms/op
                 listUser·p1.00:   32.309 ms/op

Iteration   3: 4.084 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  21.974 ms/op
                 listUser·p0.9999: 24.107 ms/op
                 listUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238144
  mean =      4.034 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2667 
    [ 2.500,  5.000) = 211135 
    [ 5.000,  7.500) = 22777 
    [ 7.500, 10.000) = 1022 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     30.912 ms/op
     p(99.9990) =     32.186 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.550 ± 1.748  ops/ms
ClientGrpc.existUser                       thrpt       3  10.671 ± 4.645  ops/ms
ClientGrpc.getUser                         thrpt       3  10.319 ± 1.772  ops/ms
ClientGrpc.listUser                        thrpt       3   7.777 ± 1.936  ops/ms
ClientGrpc.createUser                       avgt       3   3.047 ± 0.464   ms/op
ClientGrpc.existUser                        avgt       3   2.933 ± 1.059   ms/op
ClientGrpc.getUser                          avgt       3   3.044 ± 0.150   ms/op
ClientGrpc.listUser                         avgt       3   4.048 ± 0.439   ms/op
ClientGrpc.createUser                     sample  315317   3.043 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.581           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.520           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.277           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.678           ms/op
ClientGrpc.existUser                      sample  326165   2.944 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.701           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.257           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.974           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.709           ms/op
ClientGrpc.getUser                        sample  313439   3.061 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.763           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.135           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.479           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.609           ms/op
ClientGrpc.listUser                       sample  238144   4.034 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.777           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.481           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.912           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.309           ms/op
