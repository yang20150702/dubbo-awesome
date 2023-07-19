# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.773 ops/ms
# Warmup Iteration   2: 8.769 ops/ms
# Warmup Iteration   3: 10.280 ops/ms
Iteration   1: 10.410 ops/ms
Iteration   2: 10.532 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.491 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (10.410, 10.491, 10.532), stdev = 0.070
  CI (99.9%): [9.218, 11.764] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.822 ops/ms
# Warmup Iteration   2: 10.448 ops/ms
# Warmup Iteration   3: 10.666 ops/ms
Iteration   1: 10.980 ops/ms
Iteration   2: 10.712 ops/ms
Iteration   3: 10.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.865 ±(99.9%) 2.522 ops/ms [Average]
  (min, avg, max) = (10.712, 10.865, 10.980), stdev = 0.138
  CI (99.9%): [8.344, 13.387] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.840 ops/ms
# Warmup Iteration   2: 9.998 ops/ms
# Warmup Iteration   3: 10.345 ops/ms
Iteration   1: 10.555 ops/ms
Iteration   2: 10.706 ops/ms
Iteration   3: 10.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.575 ±(99.9%) 2.239 ops/ms [Average]
  (min, avg, max) = (10.463, 10.575, 10.706), stdev = 0.123
  CI (99.9%): [8.336, 12.814] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.045 ops/ms
# Warmup Iteration   2: 7.599 ops/ms
# Warmup Iteration   3: 8.085 ops/ms
Iteration   1: 8.195 ops/ms
Iteration   2: 8.132 ops/ms
Iteration   3: 8.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.190 ±(99.9%) 1.026 ops/ms [Average]
  (min, avg, max) = (8.132, 8.190, 8.244), stdev = 0.056
  CI (99.9%): [7.164, 9.216] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
Iteration   1: 3.084 ±(99.9%) 0.002 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 3.058 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.066 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (3.055, 3.066, 3.084), stdev = 0.016
  CI (99.9%): [2.782, 3.350] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.863 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.003 ms/op
Iteration   1: 2.932 ±(99.9%) 0.004 ms/op
Iteration   2: 2.905 ±(99.9%) 0.003 ms/op
Iteration   3: 2.859 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.899 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (2.859, 2.899, 2.932), stdev = 0.037
  CI (99.9%): [2.231, 3.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.192 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.004 ms/op
Iteration   1: 2.997 ±(99.9%) 0.003 ms/op
Iteration   2: 3.008 ±(99.9%) 0.002 ms/op
Iteration   3: 3.017 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.008 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.997, 3.008, 3.017), stdev = 0.010
  CI (99.9%): [2.825, 3.190] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.184 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.036 ms/op
Iteration   1: 3.867 ±(99.9%) 0.020 ms/op
Iteration   2: 3.887 ±(99.9%) 0.019 ms/op
Iteration   3: 3.870 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.875 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (3.867, 3.875, 3.887), stdev = 0.011
  CI (99.9%): [3.678, 4.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.546 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  10.548 ms/op
                 createUser·p0.9999: 26.706 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.559 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.157 ms/op
                 createUser·p0.999:  9.250 ms/op
                 createUser·p0.9999: 17.199 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   3: 3.065 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  11.649 ms/op
                 createUser·p0.9999: 30.263 ms/op
                 createUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315489
  mean =      3.041 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22714 
    [ 2.500,  5.000) = 291699 
    [ 5.000,  7.500) = 622 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =     10.462 ms/op
     p(99.9900) =     29.950 ms/op
     p(99.9990) =     30.497 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.006 ms/op
Iteration   1: 2.914 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.522 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  5.938 ms/op
                 existUser·p0.9999: 13.911 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.832 ms/op
                 existUser·p0.9999: 14.516 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   3: 2.984 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  10.478 ms/op
                 existUser·p0.9999: 22.282 ms/op
                 existUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323998
  mean =      2.962 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35510 
    [ 2.500,  5.000) = 287178 
    [ 5.000,  7.500) = 968 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.651 ms/op
     p(99.9900) =     20.448 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.161 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  6.585 ms/op
                 getUser·p0.9999: 12.749 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.549 ms/op
                 getUser·p0.9999: 19.807 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.596 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.298 ms/op
                 getUser·p0.9999: 15.622 ms/op
                 getUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314918
  mean =      3.049 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20960 
    [ 2.500,  5.000) = 292902 
    [ 5.000,  7.500) = 817 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =     19.186 ms/op
     p(99.9990) =     20.049 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.532 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.010 ms/op
Iteration   1: 3.947 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.451 ms/op
                 listUser·p0.9999: 16.624 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   2: 3.941 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.305 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.400 ms/op
                 listUser·p0.9999: 23.218 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.920 ms/op
                 listUser·p0.9999: 23.060 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243567
  mean =      3.941 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4583 
    [ 2.500,  5.000) = 215799 
    [ 5.000,  7.500) = 21964 
    [ 7.500, 10.000) = 754 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.305 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     23.597 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.491 ± 1.273  ops/ms
ClientGrpc.existUser                       thrpt       3  10.865 ± 2.522  ops/ms
ClientGrpc.getUser                         thrpt       3  10.575 ± 2.239  ops/ms
ClientGrpc.listUser                        thrpt       3   8.190 ± 1.026  ops/ms
ClientGrpc.createUser                       avgt       3   3.066 ± 0.284   ms/op
ClientGrpc.existUser                        avgt       3   2.899 ± 0.668   ms/op
ClientGrpc.getUser                          avgt       3   3.008 ± 0.183   ms/op
ClientGrpc.listUser                         avgt       3   3.875 ± 0.196   ms/op
ClientGrpc.createUser                     sample  315489   3.041 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.546           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.462           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.950           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.097           ms/op
ClientGrpc.existUser                      sample  323998   2.962 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.522           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.651           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.448           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.512           ms/op
ClientGrpc.getUser                        sample  314918   3.049 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.596           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.652           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.186           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.087           ms/op
ClientGrpc.listUser                       sample  243567   3.941 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.305           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.074           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.413           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.658           ms/op
