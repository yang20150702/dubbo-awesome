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
# Warmup Iteration   1: 2.358 ops/ms
# Warmup Iteration   2: 5.694 ops/ms
# Warmup Iteration   3: 7.083 ops/ms
Iteration   1: 7.399 ops/ms
Iteration   2: 7.436 ops/ms
Iteration   3: 7.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.391 ±(99.9%) 0.918 ops/ms [Average]
  (min, avg, max) = (7.337, 7.391, 7.436), stdev = 0.050
  CI (99.9%): [6.472, 8.309] (assumes normal distribution)


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
# Warmup Iteration   1: 4.701 ops/ms
# Warmup Iteration   2: 7.253 ops/ms
# Warmup Iteration   3: 8.049 ops/ms
Iteration   1: 8.334 ops/ms
Iteration   2: 8.093 ops/ms
Iteration   3: 8.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.196 ±(99.9%) 2.264 ops/ms [Average]
  (min, avg, max) = (8.093, 8.196, 8.334), stdev = 0.124
  CI (99.9%): [5.932, 10.460] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.599 ops/ms
# Warmup Iteration   2: 6.780 ops/ms
# Warmup Iteration   3: 7.595 ops/ms
Iteration   1: 7.539 ops/ms
Iteration   2: 7.507 ops/ms
Iteration   3: 7.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.564 ±(99.9%) 1.328 ops/ms [Average]
  (min, avg, max) = (7.507, 7.564, 7.646), stdev = 0.073
  CI (99.9%): [6.236, 8.892] (assumes normal distribution)


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
# Warmup Iteration   1: 3.832 ops/ms
# Warmup Iteration   2: 5.353 ops/ms
# Warmup Iteration   3: 5.744 ops/ms
Iteration   1: 5.812 ops/ms
Iteration   2: 5.781 ops/ms
Iteration   3: 5.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.817 ±(99.9%) 0.722 ops/ms [Average]
  (min, avg, max) = (5.781, 5.817, 5.859), stdev = 0.040
  CI (99.9%): [5.096, 6.539] (assumes normal distribution)


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
# Warmup Iteration   1: 6.553 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.405 ±(99.9%) 0.012 ms/op
Iteration   1: 4.347 ±(99.9%) 0.002 ms/op
Iteration   2: 4.328 ±(99.9%) 0.004 ms/op
Iteration   3: 4.228 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.301 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (4.228, 4.301, 4.347), stdev = 0.064
  CI (99.9%): [3.134, 5.468] (assumes normal distribution)


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
# Warmup Iteration   1: 6.230 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.003 ms/op
Iteration   1: 3.915 ±(99.9%) 0.002 ms/op
Iteration   2: 4.052 ±(99.9%) 0.002 ms/op
Iteration   3: 3.917 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.961 ±(99.9%) 1.435 ms/op [Average]
  (min, avg, max) = (3.915, 3.961, 4.052), stdev = 0.079
  CI (99.9%): [2.526, 5.397] (assumes normal distribution)


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
# Warmup Iteration   1: 6.310 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.232 ±(99.9%) 0.013 ms/op
Iteration   1: 4.162 ±(99.9%) 0.003 ms/op
Iteration   2: 4.225 ±(99.9%) 0.002 ms/op
Iteration   3: 4.043 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.144 ±(99.9%) 1.685 ms/op [Average]
  (min, avg, max) = (4.043, 4.144, 4.225), stdev = 0.092
  CI (99.9%): [2.458, 5.829] (assumes normal distribution)


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
# Warmup Iteration   1: 8.532 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.693 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.443 ±(99.9%) 0.026 ms/op
Iteration   1: 5.328 ±(99.9%) 0.016 ms/op
Iteration   2: 5.367 ±(99.9%) 0.019 ms/op
Iteration   3: 5.394 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.363 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (5.328, 5.363, 5.394), stdev = 0.033
  CI (99.9%): [4.753, 5.973] (assumes normal distribution)


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
# Warmup Iteration   1: 7.067 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.496 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.012 ms/op
Iteration   1: 4.245 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   4.104 ms/op
                 createUser·p0.90:   5.382 ms/op
                 createUser·p0.95:   5.882 ms/op
                 createUser·p0.99:   7.700 ms/op
                 createUser·p0.999:  14.632 ms/op
                 createUser·p0.9999: 18.970 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   2: 4.229 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   4.108 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.751 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  12.041 ms/op
                 createUser·p0.9999: 24.820 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   3: 4.101 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   5.038 ms/op
                 createUser·p0.95:   5.480 ms/op
                 createUser·p0.99:   7.137 ms/op
                 createUser·p0.999:  12.339 ms/op
                 createUser·p0.9999: 18.619 ms/op
                 createUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 228973
  mean =      4.191 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3937 
    [ 2.500,  5.000) = 192225 
    [ 5.000,  7.500) = 30740 
    [ 7.500, 10.000) = 1451 
    [10.000, 12.500) = 360 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     20.677 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 6.011 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.012 ms/op
Iteration   1: 3.849 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.956 ms/op
                 existUser·p0.95:   5.489 ms/op
                 existUser·p0.99:   7.324 ms/op
                 existUser·p0.999:  11.841 ms/op
                 existUser·p0.9999: 16.976 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 3.864 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   7.067 ms/op
                 existUser·p0.999:  11.203 ms/op
                 existUser·p0.9999: 24.049 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   3: 3.919 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   6.545 ms/op
                 existUser·p0.999:  10.760 ms/op
                 existUser·p0.9999: 20.699 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 247444
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7183 
    [ 2.500,  5.000) = 218982 
    [ 5.000,  7.500) = 19586 
    [ 7.500, 10.000) = 1362 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     11.125 ms/op
     p(99.9900) =     23.437 ms/op
     p(99.9990) =     25.543 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 6.072 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.370 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.013 ms/op
Iteration   1: 4.310 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.399 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  10.961 ms/op
                 getUser·p0.9999: 18.355 ms/op
                 getUser·p1.00:   18.776 ms/op

Iteration   2: 4.227 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   4.116 ms/op
                 getUser·p0.90:   5.374 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  10.441 ms/op
                 getUser·p0.9999: 16.225 ms/op
                 getUser·p1.00:   16.613 ms/op

Iteration   3: 4.155 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.791 ms/op
                 getUser·p0.999:  13.206 ms/op
                 getUser·p0.9999: 20.598 ms/op
                 getUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 226921
  mean =      4.230 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5006 
    [ 2.500,  5.000) = 184602 
    [ 5.000,  7.500) = 35065 
    [ 7.500, 10.000) = 1845 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     20.097 ms/op
     p(99.9990) =     21.750 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 8.662 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 5.846 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.646 ±(99.9%) 0.023 ms/op
Iteration   1: 5.533 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   10.699 ms/op
                 listUser·p0.999:  21.539 ms/op
                 listUser·p0.9999: 26.735 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 5.396 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.759 ms/op
                 listUser·p0.50:   5.046 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.331 ms/op
                 listUser·p0.99:   10.813 ms/op
                 listUser·p0.999:  16.144 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 5.452 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   7.397 ms/op
                 listUser·p0.95:   8.315 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  22.544 ms/op
                 listUser·p0.9999: 26.457 ms/op
                 listUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175822
  mean =      5.460 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 247 
    [ 2.500,  5.000) = 78920 
    [ 5.000,  7.500) = 80269 
    [ 7.500, 10.000) = 13626 
    [10.000, 12.500) = 2064 
    [12.500, 15.000) = 381 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      7.397 ms/op
     p(95.0000) =      8.348 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     17.575 ms/op
     p(99.9900) =     26.340 ms/op
     p(99.9990) =     27.278 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.391 ± 0.918  ops/ms
ClientGrpc.existUser                       thrpt       3   8.196 ± 2.264  ops/ms
ClientGrpc.getUser                         thrpt       3   7.564 ± 1.328  ops/ms
ClientGrpc.listUser                        thrpt       3   5.817 ± 0.722  ops/ms
ClientGrpc.createUser                       avgt       3   4.301 ± 1.167   ms/op
ClientGrpc.existUser                        avgt       3   3.961 ± 1.435   ms/op
ClientGrpc.getUser                          avgt       3   4.144 ± 1.685   ms/op
ClientGrpc.listUser                         avgt       3   5.363 ± 0.610   ms/op
ClientGrpc.createUser                     sample  228973   4.191 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.982           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.067           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.235           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.726           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.365           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.025           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.677           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.494           ms/op
ClientGrpc.existUser                      sample  247444   3.877 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.820           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.899           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.382           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.980           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.125           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.437           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.919           ms/op
ClientGrpc.getUser                        sample  226921   4.230 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.781           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.116           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.341           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.833           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.487           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.567           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.097           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.774           ms/op
ClientGrpc.listUser                       sample  175822   5.460 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.311           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.397           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.348           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.699           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.575           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.340           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.427           ms/op
