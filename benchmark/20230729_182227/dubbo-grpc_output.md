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
# Warmup Iteration   1: 2.900 ops/ms
# Warmup Iteration   2: 6.741 ops/ms
# Warmup Iteration   3: 8.550 ops/ms
Iteration   1: 8.682 ops/ms
Iteration   2: 8.859 ops/ms
Iteration   3: 8.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.813 ±(99.9%) 2.097 ops/ms [Average]
  (min, avg, max) = (8.682, 8.813, 8.898), stdev = 0.115
  CI (99.9%): [6.717, 10.910] (assumes normal distribution)


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
# Warmup Iteration   1: 5.835 ops/ms
# Warmup Iteration   2: 8.764 ops/ms
# Warmup Iteration   3: 9.288 ops/ms
Iteration   1: 9.444 ops/ms
Iteration   2: 9.500 ops/ms
Iteration   3: 9.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.494 ±(99.9%) 0.873 ops/ms [Average]
  (min, avg, max) = (9.444, 9.494, 9.539), stdev = 0.048
  CI (99.9%): [8.622, 10.367] (assumes normal distribution)


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
# Warmup Iteration   1: 5.823 ops/ms
# Warmup Iteration   2: 8.589 ops/ms
# Warmup Iteration   3: 8.917 ops/ms
Iteration   1: 9.064 ops/ms
Iteration   2: 9.033 ops/ms
Iteration   3: 8.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.996 ±(99.9%) 1.700 ops/ms [Average]
  (min, avg, max) = (8.890, 8.996, 9.064), stdev = 0.093
  CI (99.9%): [7.295, 10.696] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ops/ms
# Warmup Iteration   2: 6.498 ops/ms
# Warmup Iteration   3: 6.970 ops/ms
Iteration   1: 6.883 ops/ms
Iteration   2: 6.892 ops/ms
Iteration   3: 6.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.861 ±(99.9%) 0.826 ops/ms [Average]
  (min, avg, max) = (6.809, 6.861, 6.892), stdev = 0.045
  CI (99.9%): [6.035, 7.688] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.451 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.005 ms/op
Iteration   1: 3.542 ±(99.9%) 0.004 ms/op
Iteration   2: 3.550 ±(99.9%) 0.003 ms/op
Iteration   3: 3.559 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.550 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (3.542, 3.550, 3.559), stdev = 0.008
  CI (99.9%): [3.400, 3.701] (assumes normal distribution)


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
# Warmup Iteration   1: 5.093 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.640 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.002 ms/op
Iteration   1: 3.447 ±(99.9%) 0.003 ms/op
Iteration   2: 3.436 ±(99.9%) 0.003 ms/op
Iteration   3: 3.404 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.429 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (3.404, 3.429, 3.447), stdev = 0.022
  CI (99.9%): [3.023, 3.835] (assumes normal distribution)


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.836 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.003 ms/op
Iteration   1: 3.614 ±(99.9%) 0.004 ms/op
Iteration   2: 3.611 ±(99.9%) 0.006 ms/op
Iteration   3: 3.615 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.613 ±(99.9%) 0.040 ms/op [Average]
  (min, avg, max) = (3.611, 3.613, 3.615), stdev = 0.002
  CI (99.9%): [3.573, 3.653] (assumes normal distribution)


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
# Warmup Iteration   1: 5.875 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 5.334 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.754 ±(99.9%) 0.019 ms/op
Iteration   1: 4.717 ±(99.9%) 0.018 ms/op
Iteration   2: 4.737 ±(99.9%) 0.006 ms/op
Iteration   3: 4.671 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.708 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (4.671, 4.708, 4.737), stdev = 0.034
  CI (99.9%): [4.086, 5.330] (assumes normal distribution)


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
# Warmup Iteration   1: 5.276 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.008 ms/op
Iteration   1: 3.546 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.409 ms/op
                 createUser·p0.999:  10.254 ms/op
                 createUser·p0.9999: 15.235 ms/op
                 createUser·p1.00:   17.236 ms/op

Iteration   2: 3.586 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  8.492 ms/op
                 createUser·p0.9999: 16.679 ms/op
                 createUser·p1.00:   17.662 ms/op

Iteration   3: 3.528 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  17.309 ms/op
                 createUser·p0.9999: 20.049 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 270268
  mean =      3.553 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8377 
    [ 2.500,  5.000) = 258799 
    [ 5.000,  7.500) = 2611 
    [ 7.500, 10.000) = 220 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.112 ms/op
     p(99.9000) =      9.625 ms/op
     p(99.9900) =     19.168 ms/op
     p(99.9990) =     20.424 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 4.848 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.007 ms/op
Iteration   1: 3.438 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 23.845 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   2: 3.393 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  8.118 ms/op
                 existUser·p0.9999: 19.778 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   3: 3.450 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  7.015 ms/op
                 existUser·p0.9999: 22.306 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280060
  mean =      3.427 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10530 
    [ 2.500,  5.000) = 266830 
    [ 5.000,  7.500) = 2244 
    [ 7.500, 10.000) = 270 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =      8.355 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     23.960 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 5.165 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.009 ms/op
Iteration   1: 3.626 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  8.339 ms/op
                 getUser·p0.9999: 15.598 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   2: 3.616 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  8.439 ms/op
                 getUser·p0.9999: 16.312 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   3: 3.532 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  7.676 ms/op
                 getUser·p0.9999: 17.658 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 267295
  mean =      3.590 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 9064 
    [ 2.500,  3.750) = 166111 
    [ 3.750,  5.000) = 87708 
    [ 5.000,  6.250) = 3506 
    [ 6.250,  7.500) = 421 
    [ 7.500,  8.750) = 238 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =      8.081 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     18.251 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 6.402 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.124 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.737 ±(99.9%) 0.014 ms/op
Iteration   1: 4.658 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.357 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  14.354 ms/op
                 listUser·p0.9999: 17.666 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   2: 4.687 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.851 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  15.881 ms/op
                 listUser·p0.9999: 17.969 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   3: 4.812 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.103 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  17.712 ms/op
                 listUser·p0.9999: 21.725 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203353
  mean =      4.718 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 403 
    [ 2.500,  5.000) = 160660 
    [ 5.000,  7.500) = 37766 
    [ 7.500, 10.000) = 3998 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.718 ms/op
     p(95.0000) =      6.611 ms/op
     p(99.0000) =      8.208 ms/op
     p(99.9000) =     15.674 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.813 ± 2.097  ops/ms
ClientGrpc.existUser                       thrpt       3   9.494 ± 0.873  ops/ms
ClientGrpc.getUser                         thrpt       3   8.996 ± 1.700  ops/ms
ClientGrpc.listUser                        thrpt       3   6.861 ± 0.826  ops/ms
ClientGrpc.createUser                       avgt       3   3.550 ± 0.150   ms/op
ClientGrpc.existUser                        avgt       3   3.429 ± 0.406   ms/op
ClientGrpc.getUser                          avgt       3   3.613 ± 0.040   ms/op
ClientGrpc.listUser                         avgt       3   4.708 ± 0.622   ms/op
ClientGrpc.createUser                     sample  270268   3.553 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.572           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.149           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.112           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.625           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.168           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.513           ms/op
ClientGrpc.existUser                      sample  280060   3.427 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.770           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.964           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.355           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.807           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.379           ms/op
ClientGrpc.getUser                        sample  267295   3.590 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.838           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.081           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.334           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.416           ms/op
ClientGrpc.listUser                       sample  203353   4.718 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.262           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.208           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.674           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.988           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.020           ms/op
