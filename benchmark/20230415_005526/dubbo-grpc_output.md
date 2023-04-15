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
# Warmup Iteration   1: 3.923 ops/ms
# Warmup Iteration   2: 8.658 ops/ms
# Warmup Iteration   3: 9.809 ops/ms
Iteration   1: 10.435 ops/ms
Iteration   2: 10.514 ops/ms
Iteration   3: 10.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.482 ±(99.9%) 0.761 ops/ms [Average]
  (min, avg, max) = (10.435, 10.482, 10.514), stdev = 0.042
  CI (99.9%): [9.722, 11.243] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.176 ops/ms
# Warmup Iteration   2: 10.485 ops/ms
# Warmup Iteration   3: 10.975 ops/ms
Iteration   1: 11.205 ops/ms
Iteration   2: 11.051 ops/ms
Iteration   3: 11.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.093 ±(99.9%) 1.789 ops/ms [Average]
  (min, avg, max) = (11.022, 11.093, 11.205), stdev = 0.098
  CI (99.9%): [9.304, 12.882] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.995 ops/ms
# Warmup Iteration   2: 10.035 ops/ms
# Warmup Iteration   3: 10.458 ops/ms
Iteration   1: 10.535 ops/ms
Iteration   2: 10.515 ops/ms
Iteration   3: 10.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.538 ±(99.9%) 0.436 ops/ms [Average]
  (min, avg, max) = (10.515, 10.538, 10.563), stdev = 0.024
  CI (99.9%): [10.102, 10.973] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.669 ops/ms
# Warmup Iteration   2: 7.851 ops/ms
# Warmup Iteration   3: 8.175 ops/ms
Iteration   1: 8.177 ops/ms
Iteration   2: 8.170 ops/ms
Iteration   3: 8.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.176 ±(99.9%) 0.110 ops/ms [Average]
  (min, avg, max) = (8.170, 8.176, 8.182), stdev = 0.006
  CI (99.9%): [8.067, 8.286] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.484 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.003 ms/op
Iteration   1: 3.059 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
Iteration   3: 3.004 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.029 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.004, 3.029, 3.059), stdev = 0.027
  CI (99.9%): [2.528, 3.531] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.003 ms/op
Iteration   1: 2.877 ±(99.9%) 0.003 ms/op
Iteration   2: 2.872 ±(99.9%) 0.003 ms/op
Iteration   3: 2.843 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.864 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (2.843, 2.864, 2.877), stdev = 0.018
  CI (99.9%): [2.535, 3.193] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.249 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.003 ms/op
Iteration   1: 2.999 ±(99.9%) 0.002 ms/op
Iteration   2: 2.994 ±(99.9%) 0.004 ms/op
Iteration   3: 2.960 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.984 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.960, 2.984, 2.999), stdev = 0.021
  CI (99.9%): [2.599, 3.370] (assumes normal distribution)


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
# Warmup Iteration   1: 4.945 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.011 ms/op
Iteration   1: 3.851 ±(99.9%) 0.024 ms/op
Iteration   2: 3.857 ±(99.9%) 0.019 ms/op
Iteration   3: 3.824 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.844 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.824, 3.844, 3.857), stdev = 0.017
  CI (99.9%): [3.528, 4.160] (assumes normal distribution)


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
# Warmup Iteration   1: 4.236 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
Iteration   1: 3.040 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  7.520 ms/op
                 createUser·p0.9999: 17.957 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  10.584 ms/op
                 createUser·p0.9999: 18.499 ms/op
                 createUser·p1.00:   18.874 ms/op

Iteration   3: 3.039 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  12.108 ms/op
                 createUser·p0.9999: 36.438 ms/op
                 createUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315133
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26830 
    [ 2.500,  5.000) = 286508 
    [ 5.000,  7.500) = 1386 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =     10.303 ms/op
     p(99.9900) =     35.650 ms/op
     p(99.9990) =     36.635 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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
# Warmup Iteration   1: 3.888 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
Iteration   1: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.059 ms/op
                 existUser·p0.9999: 19.467 ms/op
                 existUser·p1.00:   19.759 ms/op

Iteration   2: 2.941 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  6.871 ms/op
                 existUser·p0.9999: 14.975 ms/op
                 existUser·p1.00:   15.401 ms/op

Iteration   3: 2.907 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.387 ms/op
                 existUser·p0.9999: 17.694 ms/op
                 existUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328170
  mean =      2.925 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 916 
    [ 1.250,  2.500) = 37622 
    [ 2.500,  3.750) = 278913 
    [ 3.750,  5.000) = 9639 
    [ 5.000,  6.250) = 561 
    [ 6.250,  7.500) = 243 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.004 ms/op
     p(99.9900) =     18.217 ms/op
     p(99.9990) =     19.717 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 4.207 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.267 ms/op
                 getUser·p0.9999: 13.099 ms/op
                 getUser·p1.00:   13.320 ms/op

Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  6.870 ms/op
                 getUser·p0.9999: 17.248 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  8.466 ms/op
                 getUser·p0.9999: 18.940 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318674
  mean =      3.011 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 498 
    [ 1.250,  2.500) = 23995 
    [ 2.500,  3.750) = 276188 
    [ 3.750,  5.000) = 16180 
    [ 5.000,  6.250) = 1084 
    [ 6.250,  7.500) = 420 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 63 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      7.457 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     19.229 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 5.515 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.930 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.011 ms/op
Iteration   1: 3.859 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 26.860 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   2: 3.843 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  15.495 ms/op
                 listUser·p0.9999: 16.985 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   3: 3.930 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.039 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  16.615 ms/op
                 listUser·p0.9999: 25.927 ms/op
                 listUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247777
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4846 
    [ 2.500,  5.000) = 221821 
    [ 5.000,  7.500) = 19898 
    [ 7.500, 10.000) = 748 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     26.477 ms/op
     p(99.9990) =     27.314 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.482 ± 0.761  ops/ms
ClientGrpc.existUser                       thrpt       3  11.093 ± 1.789  ops/ms
ClientGrpc.getUser                         thrpt       3  10.538 ± 0.436  ops/ms
ClientGrpc.listUser                        thrpt       3   8.176 ± 0.110  ops/ms
ClientGrpc.createUser                       avgt       3   3.029 ± 0.502   ms/op
ClientGrpc.existUser                        avgt       3   2.864 ± 0.329   ms/op
ClientGrpc.getUser                          avgt       3   2.984 ± 0.386   ms/op
ClientGrpc.listUser                         avgt       3   3.844 ± 0.316   ms/op
ClientGrpc.createUser                     sample  315133   3.046 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.761           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.303           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.650           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.831           ms/op
ClientGrpc.existUser                      sample  328170   2.925 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.757           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.004           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.217           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.759           ms/op
ClientGrpc.getUser                        sample  318674   3.011 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.655           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.457           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.334           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.890           ms/op
ClientGrpc.listUser                       sample  247777   3.877 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.000           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.477           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.918           ms/op
