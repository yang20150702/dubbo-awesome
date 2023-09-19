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
# Warmup Iteration   1: 4.076 ops/ms
# Warmup Iteration   2: 8.757 ops/ms
# Warmup Iteration   3: 9.848 ops/ms
Iteration   1: 9.944 ops/ms
Iteration   2: 10.157 ops/ms
Iteration   3: 10.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.107 ±(99.9%) 2.640 ops/ms [Average]
  (min, avg, max) = (9.944, 10.107, 10.220), stdev = 0.145
  CI (99.9%): [7.466, 12.747] (assumes normal distribution)


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
# Warmup Iteration   1: 7.020 ops/ms
# Warmup Iteration   2: 10.147 ops/ms
# Warmup Iteration   3: 10.369 ops/ms
Iteration   1: 10.620 ops/ms
Iteration   2: 10.779 ops/ms
Iteration   3: 10.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.674 ±(99.9%) 1.656 ops/ms [Average]
  (min, avg, max) = (10.620, 10.674, 10.779), stdev = 0.091
  CI (99.9%): [9.018, 12.330] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.800 ops/ms
# Warmup Iteration   2: 9.698 ops/ms
# Warmup Iteration   3: 10.053 ops/ms
Iteration   1: 10.040 ops/ms
Iteration   2: 10.277 ops/ms
Iteration   3: 10.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.174 ±(99.9%) 2.218 ops/ms [Average]
  (min, avg, max) = (10.040, 10.174, 10.277), stdev = 0.122
  CI (99.9%): [7.955, 12.392] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.499 ops/ms
# Warmup Iteration   2: 7.731 ops/ms
# Warmup Iteration   3: 8.128 ops/ms
Iteration   1: 8.222 ops/ms
Iteration   2: 8.024 ops/ms
Iteration   3: 8.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.141 ±(99.9%) 1.895 ops/ms [Average]
  (min, avg, max) = (8.024, 8.141, 8.222), stdev = 0.104
  CI (99.9%): [6.245, 10.036] (assumes normal distribution)


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
# Warmup Iteration   1: 4.436 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.001 ms/op
Iteration   1: 3.130 ±(99.9%) 0.002 ms/op
Iteration   2: 3.205 ±(99.9%) 0.002 ms/op
Iteration   3: 3.088 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.141 ±(99.9%) 1.086 ms/op [Average]
  (min, avg, max) = (3.088, 3.141, 3.205), stdev = 0.060
  CI (99.9%): [2.056, 4.227] (assumes normal distribution)


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
# Warmup Iteration   1: 4.064 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.001 ms/op
Iteration   1: 2.981 ±(99.9%) 0.003 ms/op
Iteration   2: 3.069 ±(99.9%) 0.002 ms/op
Iteration   3: 3.030 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.027 ±(99.9%) 0.806 ms/op [Average]
  (min, avg, max) = (2.981, 3.027, 3.069), stdev = 0.044
  CI (99.9%): [2.221, 3.832] (assumes normal distribution)


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.002 ms/op
Iteration   1: 3.166 ±(99.9%) 0.001 ms/op
Iteration   2: 3.145 ±(99.9%) 0.005 ms/op
Iteration   3: 3.082 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.131 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (3.082, 3.131, 3.166), stdev = 0.044
  CI (99.9%): [2.332, 3.929] (assumes normal distribution)


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
# Warmup Iteration   1: 5.823 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.031 ms/op
Iteration   1: 3.990 ±(99.9%) 0.039 ms/op
Iteration   2: 3.988 ±(99.9%) 0.046 ms/op
Iteration   3: 3.938 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.972 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (3.938, 3.972, 3.990), stdev = 0.030
  CI (99.9%): [3.432, 4.512] (assumes normal distribution)


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
# Warmup Iteration   1: 4.631 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
Iteration   1: 3.121 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  10.788 ms/op
                 createUser·p0.9999: 16.138 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   2: 3.148 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.539 ms/op
                 createUser·p0.999:  7.852 ms/op
                 createUser·p0.9999: 18.643 ms/op
                 createUser·p1.00:   19.530 ms/op

Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.241 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307662
  mean =      3.119 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 298 
    [ 1.250,  2.500) = 10406 
    [ 2.500,  3.750) = 277905 
    [ 3.750,  5.000) = 17365 
    [ 5.000,  6.250) = 852 
    [ 6.250,  7.500) = 460 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      9.082 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     19.852 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 4.248 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.315 ms/op
                 existUser·p0.999:  6.368 ms/op
                 existUser·p0.9999: 14.982 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.066 ms/op
                 existUser·p0.9999: 15.206 ms/op
                 existUser·p1.00:   15.811 ms/op

Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  8.482 ms/op
                 existUser·p0.9999: 17.576 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320154
  mean =      2.998 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 349 
    [ 1.250,  2.500) = 22688 
    [ 2.500,  3.750) = 285780 
    [ 3.750,  5.000) = 9940 
    [ 5.000,  6.250) = 824 
    [ 6.250,  7.500) = 299 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.159 ms/op
     p(99.9900) =     17.268 ms/op
     p(99.9990) =     17.845 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 4.478 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
Iteration   1: 3.152 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.948 ms/op
                 getUser·p0.999:  10.577 ms/op
                 getUser·p0.9999: 18.088 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.715 ms/op
                 getUser·p0.999:  7.625 ms/op
                 getUser·p0.9999: 17.461 ms/op
                 getUser·p1.00:   18.022 ms/op

Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.437 ms/op
                 getUser·p0.9999: 23.003 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302768
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8645 
    [ 2.500,  5.000) = 291967 
    [ 5.000,  7.500) = 1712 
    [ 7.500, 10.000) = 167 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      8.707 ms/op
     p(99.9900) =     22.208 ms/op
     p(99.9990) =     23.263 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 5.658 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.010 ms/op
Iteration   1: 3.872 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.058 ms/op
                 listUser·p0.9999: 15.023 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 3.961 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.785 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 16.836 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 3.934 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  15.129 ms/op
                 listUser·p0.9999: 17.846 ms/op
                 listUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244690
  mean =      3.922 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1997 
    [ 2.500,  3.750) = 103210 
    [ 3.750,  5.000) = 124333 
    [ 5.000,  6.250) = 10104 
    [ 6.250,  7.500) = 4026 
    [ 7.500,  8.750) = 440 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 167 
    [13.750, 15.000) = 126 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     17.024 ms/op
     p(99.9990) =     18.754 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.107 ± 2.640  ops/ms
ClientGrpc.existUser                       thrpt       3  10.674 ± 1.656  ops/ms
ClientGrpc.getUser                         thrpt       3  10.174 ± 2.218  ops/ms
ClientGrpc.listUser                        thrpt       3   8.141 ± 1.895  ops/ms
ClientGrpc.createUser                       avgt       3   3.141 ± 1.086   ms/op
ClientGrpc.existUser                        avgt       3   3.027 ± 0.806   ms/op
ClientGrpc.getUser                          avgt       3   3.131 ± 0.799   ms/op
ClientGrpc.listUser                         avgt       3   3.972 ± 0.540   ms/op
ClientGrpc.createUser                     sample  307662   3.119 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.663           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.082           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.300           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.988           ms/op
ClientGrpc.existUser                      sample  320154   2.998 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.788           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.159           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.268           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.891           ms/op
ClientGrpc.getUser                        sample  302768   3.169 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.635           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.694           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.707           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.208           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.364           ms/op
ClientGrpc.listUser                       sample  244690   3.922 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.865           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.538           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.795           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.024           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.661           ms/op
