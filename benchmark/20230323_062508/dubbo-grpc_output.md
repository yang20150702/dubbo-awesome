# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.605 ops/ms
# Warmup Iteration   2: 9.636 ops/ms
# Warmup Iteration   3: 10.500 ops/ms
Iteration   1: 10.974 ops/ms
Iteration   2: 10.712 ops/ms
Iteration   3: 10.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.846 ±(99.9%) 2.391 ops/ms [Average]
  (min, avg, max) = (10.712, 10.846, 10.974), stdev = 0.131
  CI (99.9%): [8.455, 13.237] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.078 ops/ms
# Warmup Iteration   2: 10.978 ops/ms
# Warmup Iteration   3: 11.327 ops/ms
Iteration   1: 11.020 ops/ms
Iteration   2: 11.457 ops/ms
Iteration   3: 11.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.351 ±(99.9%) 5.351 ops/ms [Average]
  (min, avg, max) = (11.020, 11.351, 11.577), stdev = 0.293
  CI (99.9%): [6.000, 16.702] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.519 ops/ms
# Warmup Iteration   2: 10.704 ops/ms
# Warmup Iteration   3: 10.504 ops/ms
Iteration   1: 10.826 ops/ms
Iteration   2: 10.727 ops/ms
Iteration   3: 10.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.809 ±(99.9%) 1.368 ops/ms [Average]
  (min, avg, max) = (10.727, 10.809, 10.874), stdev = 0.075
  CI (99.9%): [9.441, 12.177] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.345 ops/ms
# Warmup Iteration   2: 8.036 ops/ms
# Warmup Iteration   3: 8.338 ops/ms
Iteration   1: 8.326 ops/ms
Iteration   2: 8.508 ops/ms
Iteration   3: 8.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.463 ±(99.9%) 2.208 ops/ms [Average]
  (min, avg, max) = (8.326, 8.463, 8.555), stdev = 0.121
  CI (99.9%): [6.255, 10.670] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.933 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.008 ms/op
Iteration   1: 2.978 ±(99.9%) 0.003 ms/op
Iteration   2: 2.978 ±(99.9%) 0.003 ms/op
Iteration   3: 2.935 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.964 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (2.935, 2.964, 2.978), stdev = 0.025
  CI (99.9%): [2.506, 3.422] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.679 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.818 ±(99.9%) 0.003 ms/op
Iteration   1: 2.865 ±(99.9%) 0.004 ms/op
Iteration   2: 2.824 ±(99.9%) 0.003 ms/op
Iteration   3: 2.848 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.846 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (2.824, 2.846, 2.865), stdev = 0.021
  CI (99.9%): [2.469, 3.223] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.866 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.003 ms/op
Iteration   1: 2.953 ±(99.9%) 0.002 ms/op
Iteration   2: 2.960 ±(99.9%) 0.002 ms/op
Iteration   3: 2.937 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.950 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.937, 2.950, 2.960), stdev = 0.011
  CI (99.9%): [2.743, 3.157] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.056 ms/op
Iteration   1: 3.878 ±(99.9%) 0.026 ms/op
Iteration   2: 3.830 ±(99.9%) 0.027 ms/op
Iteration   3: 3.881 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.863 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.830, 3.863, 3.881), stdev = 0.028
  CI (99.9%): [3.343, 4.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.944 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  9.403 ms/op
                 createUser·p0.9999: 17.170 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  6.857 ms/op
                 createUser·p0.9999: 20.480 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.513 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.290 ms/op
                 createUser·p0.9999: 15.221 ms/op
                 createUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323684
  mean =      2.966 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37286 
    [ 2.500,  5.000) = 284918 
    [ 5.000,  7.500) = 1142 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.763 ms/op
     p(99.9900) =     18.845 ms/op
     p(99.9990) =     20.603 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.679 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 2.898 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.868 ±(99.9%) 0.005 ms/op
Iteration   1: 2.777 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  5.872 ms/op
                 existUser·p0.9999: 10.772 ms/op
                 existUser·p1.00:   11.239 ms/op

Iteration   2: 2.883 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.390 ms/op
                 existUser·p0.999:  6.190 ms/op
                 existUser·p0.9999: 12.532 ms/op
                 existUser·p1.00:   12.763 ms/op

Iteration   3: 2.765 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.280 ms/op
                 existUser·p0.9999: 14.072 ms/op
                 existUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 341644
  mean =      2.807 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5307 
    [ 1.250,  2.500) = 56946 
    [ 2.500,  3.750) = 268108 
    [ 3.750,  5.000) = 10457 
    [ 5.000,  6.250) = 510 
    [ 6.250,  7.500) = 105 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      6.103 ms/op
     p(99.9900) =     12.534 ms/op
     p(99.9990) =     14.292 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.940 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
Iteration   1: 2.979 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.706 ms/op
                 getUser·p0.9999: 11.043 ms/op
                 getUser·p1.00:   11.272 ms/op

Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  6.697 ms/op
                 getUser·p0.9999: 13.202 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.651 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.257 ms/op
                 getUser·p0.999:  7.381 ms/op
                 getUser·p0.9999: 17.046 ms/op
                 getUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320867
  mean =      2.991 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1398 
    [ 1.250,  2.500) = 25790 
    [ 2.500,  3.750) = 280690 
    [ 3.750,  5.000) = 12163 
    [ 5.000,  6.250) = 376 
    [ 6.250,  7.500) = 191 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.851 ms/op
     p(99.9900) =     16.213 ms/op
     p(99.9990) =     18.900 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.261 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.010 ms/op
Iteration   1: 3.871 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  11.721 ms/op
                 listUser·p0.9999: 13.930 ms/op
                 listUser·p1.00:   15.647 ms/op

Iteration   2: 3.843 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 15.259 ms/op
                 listUser·p1.00:   16.351 ms/op

Iteration   3: 3.719 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   6.349 ms/op
                 listUser·p0.999:  12.877 ms/op
                 listUser·p0.9999: 21.424 ms/op
                 listUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251910
  mean =      3.810 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5789 
    [ 2.500,  5.000) = 227466 
    [ 5.000,  7.500) = 17468 
    [ 7.500, 10.000) = 689 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     12.945 ms/op
     p(99.9900) =     19.616 ms/op
     p(99.9990) =     24.136 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.846 ± 2.391  ops/ms
ClientGrpc.existUser                       thrpt       3  11.351 ± 5.351  ops/ms
ClientGrpc.getUser                         thrpt       3  10.809 ± 1.368  ops/ms
ClientGrpc.listUser                        thrpt       3   8.463 ± 2.208  ops/ms
ClientGrpc.createUser                       avgt       3   2.964 ± 0.458   ms/op
ClientGrpc.existUser                        avgt       3   2.846 ± 0.377   ms/op
ClientGrpc.getUser                          avgt       3   2.950 ± 0.207   ms/op
ClientGrpc.listUser                         avgt       3   3.863 ± 0.520   ms/op
ClientGrpc.createUser                     sample  323684   2.966 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.513           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.763           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.845           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.677           ms/op
ClientGrpc.existUser                      sample  341644   2.807 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.534           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.103           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          12.534           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.385           ms/op
ClientGrpc.getUser                        sample  320867   2.991 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.651           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.851           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.213           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.038           ms/op
ClientGrpc.listUser                       sample  251910   3.810 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.956           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.945           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.616           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.296           ms/op
