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
# Warmup Iteration   1: 3.262 ops/ms
# Warmup Iteration   2: 6.877 ops/ms
# Warmup Iteration   3: 8.286 ops/ms
Iteration   1: 8.751 ops/ms
Iteration   2: 9.150 ops/ms
Iteration   3: 8.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.929 ±(99.9%) 3.702 ops/ms [Average]
  (min, avg, max) = (8.751, 8.929, 9.150), stdev = 0.203
  CI (99.9%): [5.227, 12.631] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.750 ops/ms
# Warmup Iteration   2: 9.030 ops/ms
# Warmup Iteration   3: 9.279 ops/ms
Iteration   1: 9.371 ops/ms
Iteration   2: 9.476 ops/ms
Iteration   3: 9.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.537 ±(99.9%) 3.713 ops/ms [Average]
  (min, avg, max) = (9.371, 9.537, 9.764), stdev = 0.204
  CI (99.9%): [5.824, 13.250] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.962 ops/ms
# Warmup Iteration   2: 8.629 ops/ms
# Warmup Iteration   3: 8.986 ops/ms
Iteration   1: 8.966 ops/ms
Iteration   2: 8.773 ops/ms
Iteration   3: 9.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.960 ±(99.9%) 3.371 ops/ms [Average]
  (min, avg, max) = (8.773, 8.960, 9.142), stdev = 0.185
  CI (99.9%): [5.589, 12.332] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.285 ops/ms
# Warmup Iteration   2: 6.380 ops/ms
# Warmup Iteration   3: 6.671 ops/ms
Iteration   1: 6.884 ops/ms
Iteration   2: 6.833 ops/ms
Iteration   3: 6.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.822 ±(99.9%) 1.226 ops/ms [Average]
  (min, avg, max) = (6.751, 6.822, 6.884), stdev = 0.067
  CI (99.9%): [5.597, 8.048] (assumes normal distribution)


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
# Warmup Iteration   1: 4.928 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.004 ms/op
Iteration   1: 3.681 ±(99.9%) 0.003 ms/op
Iteration   2: 3.500 ±(99.9%) 0.003 ms/op
Iteration   3: 3.661 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.614 ±(99.9%) 1.809 ms/op [Average]
  (min, avg, max) = (3.500, 3.614, 3.681), stdev = 0.099
  CI (99.9%): [1.806, 5.423] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.562 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.003 ms/op
Iteration   1: 3.299 ±(99.9%) 0.004 ms/op
Iteration   2: 3.210 ±(99.9%) 0.003 ms/op
Iteration   3: 3.339 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.283 ±(99.9%) 1.202 ms/op [Average]
  (min, avg, max) = (3.210, 3.283, 3.339), stdev = 0.066
  CI (99.9%): [2.081, 4.484] (assumes normal distribution)


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
# Warmup Iteration   1: 5.103 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.738 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.666 ±(99.9%) 0.003 ms/op
Iteration   1: 3.538 ±(99.9%) 0.004 ms/op
Iteration   2: 3.523 ±(99.9%) 0.004 ms/op
Iteration   3: 3.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.522 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (3.506, 3.522, 3.538), stdev = 0.016
  CI (99.9%): [3.231, 3.814] (assumes normal distribution)


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
# Warmup Iteration   1: 5.523 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 5.148 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.818 ±(99.9%) 0.010 ms/op
Iteration   1: 4.728 ±(99.9%) 0.015 ms/op
Iteration   2: 4.712 ±(99.9%) 0.019 ms/op
Iteration   3: 4.753 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.731 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (4.712, 4.731, 4.753), stdev = 0.021
  CI (99.9%): [4.350, 5.112] (assumes normal distribution)


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
# Warmup Iteration   1: 4.947 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.009 ms/op
Iteration   1: 3.423 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  9.495 ms/op
                 createUser·p0.9999: 18.010 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   2: 3.445 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.609 ms/op
                 createUser·p0.999:  8.834 ms/op
                 createUser·p0.9999: 28.948 ms/op
                 createUser·p1.00:   29.360 ms/op

Iteration   3: 3.448 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  11.183 ms/op
                 createUser·p0.9999: 27.886 ms/op
                 createUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 279199
  mean =      3.439 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11919 
    [ 2.500,  5.000) = 262368 
    [ 5.000,  7.500) = 4192 
    [ 7.500, 10.000) = 464 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     28.481 ms/op
     p(99.9990) =     29.236 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 4.619 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.007 ms/op
Iteration   1: 3.264 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  7.881 ms/op
                 existUser·p0.9999: 14.962 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   2: 3.298 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  7.873 ms/op
                 existUser·p0.9999: 18.426 ms/op
                 existUser·p1.00:   18.809 ms/op

Iteration   3: 3.285 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  7.856 ms/op
                 existUser·p0.9999: 20.366 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 292362
  mean =      3.282 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20775 
    [ 2.500,  5.000) = 267810 
    [ 5.000,  7.500) = 3338 
    [ 7.500, 10.000) = 310 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =      7.870 ms/op
     p(99.9900) =     18.597 ms/op
     p(99.9990) =     20.682 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 5.000 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.425 ±(99.9%) 0.008 ms/op
Iteration   1: 3.510 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  11.302 ms/op
                 getUser·p0.9999: 15.119 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 3.473 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.600 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  11.827 ms/op
                 getUser·p0.9999: 20.976 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   3: 3.506 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.709 ms/op
                 getUser·p0.999:  8.283 ms/op
                 getUser·p0.9999: 20.176 ms/op
                 getUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 274479
  mean =      3.496 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11572 
    [ 2.500,  5.000) = 256330 
    [ 5.000,  7.500) = 5650 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     10.600 ms/op
     p(99.9900) =     20.451 ms/op
     p(99.9990) =     21.160 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 5.323 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.793 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.638 ±(99.9%) 0.014 ms/op
Iteration   1: 4.565 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   6.554 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 17.202 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   2: 4.521 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.546 ms/op
                 listUser·p0.95:   6.496 ms/op
                 listUser·p0.99:   8.010 ms/op
                 listUser·p0.999:  16.552 ms/op
                 listUser·p0.9999: 22.739 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   3: 4.716 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.980 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  21.513 ms/op
                 listUser·p0.9999: 32.153 ms/op
                 listUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208601
  mean =      4.599 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 538 
    [ 2.500,  5.000) = 166264 
    [ 5.000,  7.500) = 37293 
    [ 7.500, 10.000) = 3666 
    [10.000, 12.500) = 417 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.759 ms/op
     p(95.0000) =      6.627 ms/op
     p(99.0000) =      8.348 ms/op
     p(99.9000) =     16.391 ms/op
     p(99.9900) =     31.425 ms/op
     p(99.9990) =     32.888 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.929 ± 3.702  ops/ms
ClientGrpc.existUser                       thrpt       3   9.537 ± 3.713  ops/ms
ClientGrpc.getUser                         thrpt       3   8.960 ± 3.371  ops/ms
ClientGrpc.listUser                        thrpt       3   6.822 ± 1.226  ops/ms
ClientGrpc.createUser                       avgt       3   3.614 ± 1.809   ms/op
ClientGrpc.existUser                        avgt       3   3.283 ± 1.202   ms/op
ClientGrpc.getUser                          avgt       3   3.522 ± 0.291   ms/op
ClientGrpc.listUser                         avgt       3   4.731 ± 0.381   ms/op
ClientGrpc.createUser                     sample  279199   3.439 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.758           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.387           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.116           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.505           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.306           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.481           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.360           ms/op
ClientGrpc.existUser                      sample  292362   3.282 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.602           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.273           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.870           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.597           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.808           ms/op
ClientGrpc.getUser                        sample  274479   3.496 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.600           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.428           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.792           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.600           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.451           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.234           ms/op
ClientGrpc.listUser                       sample  208601   4.599 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.157           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.399           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.627           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.348           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.391           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.425           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.997           ms/op
