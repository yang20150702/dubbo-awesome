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
# Warmup Iteration   1: 4.428 ops/ms
# Warmup Iteration   2: 8.436 ops/ms
# Warmup Iteration   3: 9.648 ops/ms
Iteration   1: 10.490 ops/ms
Iteration   2: 10.291 ops/ms
Iteration   3: 10.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.369 ±(99.9%) 1.940 ops/ms [Average]
  (min, avg, max) = (10.291, 10.369, 10.490), stdev = 0.106
  CI (99.9%): [8.430, 12.309] (assumes normal distribution)


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
# Warmup Iteration   1: 6.978 ops/ms
# Warmup Iteration   2: 9.797 ops/ms
# Warmup Iteration   3: 10.368 ops/ms
Iteration   1: 10.374 ops/ms
Iteration   2: 10.302 ops/ms
Iteration   3: 10.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.395 ±(99.9%) 1.917 ops/ms [Average]
  (min, avg, max) = (10.302, 10.395, 10.509), stdev = 0.105
  CI (99.9%): [8.478, 12.313] (assumes normal distribution)


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
# Warmup Iteration   1: 6.703 ops/ms
# Warmup Iteration   2: 9.419 ops/ms
# Warmup Iteration   3: 9.706 ops/ms
Iteration   1: 9.727 ops/ms
Iteration   2: 10.044 ops/ms
Iteration   3: 9.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.914 ±(99.9%) 3.030 ops/ms [Average]
  (min, avg, max) = (9.727, 9.914, 10.044), stdev = 0.166
  CI (99.9%): [6.884, 12.944] (assumes normal distribution)


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
# Warmup Iteration   1: 5.233 ops/ms
# Warmup Iteration   2: 7.596 ops/ms
# Warmup Iteration   3: 8.071 ops/ms
Iteration   1: 8.197 ops/ms
Iteration   2: 8.285 ops/ms
Iteration   3: 8.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.247 ±(99.9%) 0.827 ops/ms [Average]
  (min, avg, max) = (8.197, 8.247, 8.285), stdev = 0.045
  CI (99.9%): [7.421, 9.074] (assumes normal distribution)


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.002 ms/op
Iteration   1: 3.134 ±(99.9%) 0.002 ms/op
Iteration   2: 3.194 ±(99.9%) 0.002 ms/op
Iteration   3: 3.195 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.174 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (3.134, 3.174, 3.195), stdev = 0.035
  CI (99.9%): [2.534, 3.815] (assumes normal distribution)


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
# Warmup Iteration   1: 3.735 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.002 ms/op
Iteration   1: 2.930 ±(99.9%) 0.004 ms/op
Iteration   2: 2.990 ±(99.9%) 0.001 ms/op
Iteration   3: 2.999 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.973 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (2.930, 2.973, 2.999), stdev = 0.038
  CI (99.9%): [2.287, 3.659] (assumes normal distribution)


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.002 ms/op
Iteration   1: 3.226 ±(99.9%) 0.002 ms/op
Iteration   2: 3.180 ±(99.9%) 0.003 ms/op
Iteration   3: 3.226 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.211 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (3.180, 3.211, 3.226), stdev = 0.027
  CI (99.9%): [2.726, 3.695] (assumes normal distribution)


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
# Warmup Iteration   1: 5.605 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.035 ms/op
Iteration   1: 3.955 ±(99.9%) 0.019 ms/op
Iteration   2: 3.937 ±(99.9%) 0.009 ms/op
Iteration   3: 3.879 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.924 ±(99.9%) 0.718 ms/op [Average]
  (min, avg, max) = (3.879, 3.924, 3.955), stdev = 0.039
  CI (99.9%): [3.206, 4.641] (assumes normal distribution)


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
# Warmup Iteration   1: 4.336 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.008 ms/op
Iteration   1: 3.130 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  7.928 ms/op
                 createUser·p0.9999: 16.590 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  8.405 ms/op
                 createUser·p0.9999: 20.662 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   3: 3.165 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.079 ms/op
                 createUser·p0.999:  11.074 ms/op
                 createUser·p0.9999: 20.477 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305435
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14117 
    [ 2.500,  5.000) = 288070 
    [ 5.000,  7.500) = 2721 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.054 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     21.227 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.006 ms/op
Iteration   1: 2.996 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.989 ms/op
                 existUser·p0.9999: 12.326 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   2: 3.055 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.324 ms/op
                 existUser·p0.9999: 12.471 ms/op
                 existUser·p1.00:   13.074 ms/op

Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.053 ms/op
                 existUser·p0.9999: 17.498 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318377
  mean =      3.015 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1064 
    [ 1.250,  2.500) = 19816 
    [ 2.500,  3.750) = 284730 
    [ 3.750,  5.000) = 11353 
    [ 5.000,  6.250) = 823 
    [ 6.250,  7.500) = 399 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.821 ms/op
     p(99.9900) =     15.581 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.006 ms/op
Iteration   1: 3.143 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  10.392 ms/op
                 getUser·p0.9999: 19.158 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   2: 3.222 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.166 ms/op
                 getUser·p0.9999: 14.943 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   3: 3.166 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.426 ms/op
                 getUser·p0.999:  8.784 ms/op
                 getUser·p0.9999: 14.336 ms/op
                 getUser·p1.00:   14.565 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302057
  mean =      3.177 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 752 
    [ 1.250,  2.500) = 6717 
    [ 2.500,  3.750) = 265342 
    [ 3.750,  5.000) = 27299 
    [ 5.000,  6.250) = 1037 
    [ 6.250,  7.500) = 382 
    [ 7.500,  8.750) = 128 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 107 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      9.909 ms/op
     p(99.9900) =     18.252 ms/op
     p(99.9990) =     19.463 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 5.078 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.010 ms/op
Iteration   1: 3.909 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  12.438 ms/op
                 listUser·p0.9999: 13.609 ms/op
                 listUser·p1.00:   14.877 ms/op

Iteration   2: 3.766 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  12.943 ms/op
                 listUser·p0.9999: 15.082 ms/op
                 listUser·p1.00:   15.860 ms/op

Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.360 ms/op
                 listUser·p0.9999: 20.100 ms/op
                 listUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248225
  mean =      3.867 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2225 
    [ 2.500,  5.000) = 233275 
    [ 5.000,  7.500) = 11640 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     13.071 ms/op
     p(99.9900) =     17.890 ms/op
     p(99.9990) =     21.043 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.369 ± 1.940  ops/ms
ClientGrpc.existUser                       thrpt       3  10.395 ± 1.917  ops/ms
ClientGrpc.getUser                         thrpt       3   9.914 ± 3.030  ops/ms
ClientGrpc.listUser                        thrpt       3   8.247 ± 0.827  ops/ms
ClientGrpc.createUser                       avgt       3   3.174 ± 0.641   ms/op
ClientGrpc.existUser                        avgt       3   2.973 ± 0.686   ms/op
ClientGrpc.getUser                          avgt       3   3.211 ± 0.484   ms/op
ClientGrpc.listUser                         avgt       3   3.924 ± 0.718   ms/op
ClientGrpc.createUser                     sample  305435   3.143 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.691           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.054           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.389           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.349           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.430           ms/op
ClientGrpc.existUser                      sample  318377   3.015 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.653           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.982           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.821           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.581           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.399           ms/op
ClientGrpc.getUser                        sample  302057   3.177 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.753           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.909           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.252           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.530           ms/op
ClientGrpc.listUser                       sample  248225   3.867 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.278           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.301           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.595           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.071           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.890           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.201           ms/op
