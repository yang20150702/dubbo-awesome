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
# Warmup Iteration   1: 4.630 ops/ms
# Warmup Iteration   2: 9.054 ops/ms
# Warmup Iteration   3: 10.185 ops/ms
Iteration   1: 10.689 ops/ms
Iteration   2: 10.752 ops/ms
Iteration   3: 10.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.778 ±(99.9%) 1.897 ops/ms [Average]
  (min, avg, max) = (10.689, 10.778, 10.892), stdev = 0.104
  CI (99.9%): [8.881, 12.675] (assumes normal distribution)


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
# Warmup Iteration   1: 7.800 ops/ms
# Warmup Iteration   2: 11.037 ops/ms
# Warmup Iteration   3: 11.023 ops/ms
Iteration   1: 11.016 ops/ms
Iteration   2: 11.369 ops/ms
Iteration   3: 11.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.206 ±(99.9%) 3.254 ops/ms [Average]
  (min, avg, max) = (11.016, 11.206, 11.369), stdev = 0.178
  CI (99.9%): [7.952, 14.460] (assumes normal distribution)


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
# Warmup Iteration   1: 7.113 ops/ms
# Warmup Iteration   2: 10.294 ops/ms
# Warmup Iteration   3: 10.771 ops/ms
Iteration   1: 10.509 ops/ms
Iteration   2: 10.707 ops/ms
Iteration   3: 10.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.645 ±(99.9%) 2.153 ops/ms [Average]
  (min, avg, max) = (10.509, 10.645, 10.719), stdev = 0.118
  CI (99.9%): [8.492, 12.798] (assumes normal distribution)


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
# Warmup Iteration   1: 6.263 ops/ms
# Warmup Iteration   2: 8.071 ops/ms
# Warmup Iteration   3: 8.330 ops/ms
Iteration   1: 8.156 ops/ms
Iteration   2: 8.158 ops/ms
Iteration   3: 8.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.159 ±(99.9%) 0.074 ops/ms [Average]
  (min, avg, max) = (8.156, 8.159, 8.164), stdev = 0.004
  CI (99.9%): [8.085, 8.233] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.066 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.002 ms/op
Iteration   1: 3.017 ±(99.9%) 0.003 ms/op
Iteration   2: 2.984 ±(99.9%) 0.003 ms/op
Iteration   3: 2.993 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.998 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (2.984, 2.998, 3.017), stdev = 0.017
  CI (99.9%): [2.689, 3.308] (assumes normal distribution)


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.892 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.003 ms/op
Iteration   1: 2.874 ±(99.9%) 0.003 ms/op
Iteration   2: 2.900 ±(99.9%) 0.004 ms/op
Iteration   3: 2.894 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.889 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (2.874, 2.889, 2.900), stdev = 0.014
  CI (99.9%): [2.642, 3.136] (assumes normal distribution)


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.003 ms/op
Iteration   1: 2.998 ±(99.9%) 0.003 ms/op
Iteration   2: 2.945 ±(99.9%) 0.005 ms/op
Iteration   3: 2.996 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.980 ±(99.9%) 0.543 ms/op [Average]
  (min, avg, max) = (2.945, 2.980, 2.998), stdev = 0.030
  CI (99.9%): [2.437, 3.523] (assumes normal distribution)


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.032 ms/op
Iteration   1: 4.001 ±(99.9%) 0.017 ms/op
Iteration   2: 3.911 ±(99.9%) 0.018 ms/op
Iteration   3: 3.884 ±(99.9%) 0.051 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.932 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (3.884, 3.932, 4.001), stdev = 0.061
  CI (99.9%): [2.816, 5.049] (assumes normal distribution)


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
# Warmup Iteration   1: 3.974 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  10.512 ms/op
                 createUser·p0.9999: 13.275 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   2: 2.944 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.629 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.559 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.398 ms/op
                 createUser·p0.9999: 12.798 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.490 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  9.633 ms/op
                 createUser·p0.9999: 18.757 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321936
  mean =      2.980 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1182 
    [ 1.250,  2.500) = 23816 
    [ 2.500,  3.750) = 286390 
    [ 3.750,  5.000) = 9522 
    [ 5.000,  6.250) = 503 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 83 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.689 ms/op
     p(99.9900) =     15.447 ms/op
     p(99.9990) =     19.031 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.877 ±(99.9%) 0.006 ms/op
Iteration   1: 2.878 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  5.693 ms/op
                 existUser·p0.9999: 12.071 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   2: 2.906 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.667 ms/op
                 existUser·p0.9999: 16.581 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  9.893 ms/op
                 existUser·p0.9999: 15.426 ms/op
                 existUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330273
  mean =      2.906 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1403 
    [ 1.250,  2.500) = 33999 
    [ 2.500,  3.750) = 285961 
    [ 3.750,  5.000) = 7772 
    [ 5.000,  6.250) = 730 
    [ 6.250,  7.500) = 170 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.775 ms/op
     p(99.9900) =     15.759 ms/op
     p(99.9990) =     16.752 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.275 ms/op
                 getUser·p0.9999: 19.592 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.414 ms/op
                 getUser·p0.9999: 15.106 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   3: 3.020 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  6.193 ms/op
                 getUser·p0.9999: 15.831 ms/op
                 getUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318836
  mean =      3.010 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20744 
    [ 2.500,  5.000) = 296945 
    [ 5.000,  7.500) = 992 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.300 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     24.697 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 5.183 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.010 ms/op
Iteration   1: 3.988 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  12.485 ms/op
                 listUser·p0.9999: 16.071 ms/op
                 listUser·p1.00:   16.679 ms/op

Iteration   2: 3.932 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  13.140 ms/op
                 listUser·p0.9999: 14.992 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 3.895 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.363 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243710
  mean =      3.938 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3408 
    [ 2.500,  5.000) = 219484 
    [ 5.000,  7.500) = 19499 
    [ 7.500, 10.000) = 863 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     19.681 ms/op
     p(99.9990) =     20.783 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.778 ± 1.897  ops/ms
ClientGrpc.existUser                       thrpt       3  11.206 ± 3.254  ops/ms
ClientGrpc.getUser                         thrpt       3  10.645 ± 2.153  ops/ms
ClientGrpc.listUser                        thrpt       3   8.159 ± 0.074  ops/ms
ClientGrpc.createUser                       avgt       3   2.998 ± 0.310   ms/op
ClientGrpc.existUser                        avgt       3   2.889 ± 0.247   ms/op
ClientGrpc.getUser                          avgt       3   2.980 ± 0.543   ms/op
ClientGrpc.listUser                         avgt       3   3.932 ± 1.117   ms/op
ClientGrpc.createUser                     sample  321936   2.980 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.490           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.404           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.689           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.447           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.104           ms/op
ClientGrpc.existUser                      sample  330273   2.906 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.601           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.775           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.759           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.908           ms/op
ClientGrpc.getUser                        sample  318836   3.010 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.725           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.300           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.137           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.690           ms/op
ClientGrpc.listUser                       sample  243710   3.938 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.991           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.304           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.681           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.873           ms/op
