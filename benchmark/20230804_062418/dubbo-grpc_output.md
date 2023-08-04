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
# Warmup Iteration   1: 3.469 ops/ms
# Warmup Iteration   2: 8.146 ops/ms
# Warmup Iteration   3: 9.141 ops/ms
Iteration   1: 9.913 ops/ms
Iteration   2: 10.068 ops/ms
Iteration   3: 10.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.053 ±(99.9%) 2.432 ops/ms [Average]
  (min, avg, max) = (9.913, 10.053, 10.178), stdev = 0.133
  CI (99.9%): [7.621, 12.485] (assumes normal distribution)


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
# Warmup Iteration   1: 7.323 ops/ms
# Warmup Iteration   2: 10.091 ops/ms
# Warmup Iteration   3: 10.700 ops/ms
Iteration   1: 10.795 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.567 ±(99.9%) 4.315 ops/ms [Average]
  (min, avg, max) = (10.322, 10.567, 10.795), stdev = 0.237
  CI (99.9%): [6.252, 14.883] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.347 ops/ms
# Warmup Iteration   2: 9.428 ops/ms
# Warmup Iteration   3: 9.807 ops/ms
Iteration   1: 9.592 ops/ms
Iteration   2: 10.026 ops/ms
Iteration   3: 9.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.776 ±(99.9%) 4.092 ops/ms [Average]
  (min, avg, max) = (9.592, 9.776, 10.026), stdev = 0.224
  CI (99.9%): [5.685, 13.868] (assumes normal distribution)


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
# Warmup Iteration   1: 5.473 ops/ms
# Warmup Iteration   2: 7.031 ops/ms
# Warmup Iteration   3: 7.706 ops/ms
Iteration   1: 7.262 ops/ms
Iteration   2: 7.603 ops/ms
Iteration   3: 7.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.581 ±(99.9%) 5.631 ops/ms [Average]
  (min, avg, max) = (7.262, 7.581, 7.878), stdev = 0.309
  CI (99.9%): [1.950, 13.212] (assumes normal distribution)


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
# Warmup Iteration   1: 4.480 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.003 ms/op
Iteration   1: 3.121 ±(99.9%) 0.005 ms/op
Iteration   2: 3.168 ±(99.9%) 0.003 ms/op
Iteration   3: 3.221 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.170 ±(99.9%) 0.913 ms/op [Average]
  (min, avg, max) = (3.121, 3.170, 3.221), stdev = 0.050
  CI (99.9%): [2.257, 4.083] (assumes normal distribution)


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
# Warmup Iteration   1: 4.413 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.002 ms/op
Iteration   1: 3.047 ±(99.9%) 0.002 ms/op
Iteration   2: 3.014 ±(99.9%) 0.002 ms/op
Iteration   3: 3.160 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.074 ±(99.9%) 1.389 ms/op [Average]
  (min, avg, max) = (3.014, 3.074, 3.160), stdev = 0.076
  CI (99.9%): [1.685, 4.463] (assumes normal distribution)


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
# Warmup Iteration   1: 4.584 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.004 ms/op
Iteration   1: 3.094 ±(99.9%) 0.003 ms/op
Iteration   2: 3.117 ±(99.9%) 0.004 ms/op
Iteration   3: 3.120 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.110 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (3.094, 3.110, 3.120), stdev = 0.014
  CI (99.9%): [2.849, 3.372] (assumes normal distribution)


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
# Warmup Iteration   1: 5.710 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.017 ms/op
Iteration   1: 4.147 ±(99.9%) 0.020 ms/op
Iteration   2: 4.166 ±(99.9%) 0.024 ms/op
Iteration   3: 4.143 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.152 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (4.143, 4.152, 4.166), stdev = 0.012
  CI (99.9%): [3.928, 4.376] (assumes normal distribution)


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
# Warmup Iteration   1: 4.492 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
Iteration   1: 3.155 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.079 ms/op
                 createUser·p0.999:  8.204 ms/op
                 createUser·p0.9999: 13.547 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.948 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 15.833 ms/op
                 createUser·p1.00:   16.318 ms/op

Iteration   3: 3.182 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  11.812 ms/op
                 createUser·p0.9999: 18.610 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305287
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17100 
    [ 2.500,  5.000) = 284892 
    [ 5.000,  7.500) = 2638 
    [ 7.500, 10.000) = 396 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =      8.822 ms/op
     p(99.9900) =     17.938 ms/op
     p(99.9990) =     20.155 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  8.854 ms/op
                 existUser·p0.9999: 14.685 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.503 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  11.742 ms/op
                 existUser·p0.9999: 15.046 ms/op
                 existUser·p1.00:   15.663 ms/op

Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.460 ms/op
                 existUser·p0.999:  9.807 ms/op
                 existUser·p0.9999: 19.518 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 308928
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19478 
    [ 2.500,  5.000) = 284892 
    [ 5.000,  7.500) = 3510 
    [ 7.500, 10.000) = 794 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     16.617 ms/op
     p(99.9990) =     20.606 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 4.500 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.008 ms/op
Iteration   1: 3.205 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  8.949 ms/op
                 getUser·p0.9999: 22.151 ms/op
                 getUser·p1.00:   22.544 ms/op

Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.906 ms/op
                 getUser·p0.999:  7.307 ms/op
                 getUser·p0.9999: 19.949 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   3: 3.184 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  8.061 ms/op
                 getUser·p0.9999: 22.900 ms/op
                 getUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302507
  mean =      3.172 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14614 
    [ 2.500,  5.000) = 284774 
    [ 5.000,  7.500) = 2584 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.022 ms/op
     p(99.9000) =      8.192 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 5.659 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.537 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.240 ±(99.9%) 0.016 ms/op
Iteration   1: 4.194 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.242 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  15.153 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 4.261 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   5.603 ms/op
                 listUser·p0.95:   6.357 ms/op
                 listUser·p0.99:   8.233 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 4.283 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  21.910 ms/op
                 listUser·p0.9999: 26.806 ms/op
                 listUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 226056
  mean =      4.246 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2425 
    [ 2.500,  5.000) = 187342 
    [ 5.000,  7.500) = 32751 
    [ 7.500, 10.000) = 2664 
    [10.000, 12.500) = 444 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.332 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     17.169 ms/op
     p(99.9900) =     25.788 ms/op
     p(99.9990) =     28.122 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.053 ± 2.432  ops/ms
ClientGrpc.existUser                       thrpt       3  10.567 ± 4.315  ops/ms
ClientGrpc.getUser                         thrpt       3   9.776 ± 4.092  ops/ms
ClientGrpc.listUser                        thrpt       3   7.581 ± 5.631  ops/ms
ClientGrpc.createUser                       avgt       3   3.170 ± 0.913   ms/op
ClientGrpc.existUser                        avgt       3   3.074 ± 1.389   ms/op
ClientGrpc.getUser                          avgt       3   3.110 ± 0.262   ms/op
ClientGrpc.listUser                         avgt       3   4.152 ± 0.224   ms/op
ClientGrpc.createUser                     sample  305287   3.145 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.773           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.079           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.822           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.938           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.644           ms/op
ClientGrpc.existUser                      sample  308928   3.106 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.503           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.554           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.568           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.617           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.775           ms/op
ClientGrpc.getUser                        sample  302507   3.172 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.730           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.022           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.192           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.151           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.757           ms/op
ClientGrpc.listUser                       sample  226056   4.246 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.868           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.002           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.332           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.169           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.788           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.279           ms/op
