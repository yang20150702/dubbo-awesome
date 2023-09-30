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
# Warmup Iteration   1: 4.398 ops/ms
# Warmup Iteration   2: 9.222 ops/ms
# Warmup Iteration   3: 9.734 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.297 ops/ms
Iteration   3: 10.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.492 ±(99.9%) 3.256 ops/ms [Average]
  (min, avg, max) = (10.297, 10.492, 10.647), stdev = 0.178
  CI (99.9%): [7.236, 13.748] (assumes normal distribution)


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
# Warmup Iteration   1: 7.950 ops/ms
# Warmup Iteration   2: 10.622 ops/ms
# Warmup Iteration   3: 10.642 ops/ms
Iteration   1: 10.800 ops/ms
Iteration   2: 10.813 ops/ms
Iteration   3: 10.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.782 ±(99.9%) 0.790 ops/ms [Average]
  (min, avg, max) = (10.733, 10.782, 10.813), stdev = 0.043
  CI (99.9%): [9.992, 11.572] (assumes normal distribution)


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
# Warmup Iteration   1: 7.465 ops/ms
# Warmup Iteration   2: 9.683 ops/ms
# Warmup Iteration   3: 10.083 ops/ms
Iteration   1: 10.102 ops/ms
Iteration   2: 10.118 ops/ms
Iteration   3: 10.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.172 ±(99.9%) 1.962 ops/ms [Average]
  (min, avg, max) = (10.102, 10.172, 10.296), stdev = 0.108
  CI (99.9%): [8.210, 12.133] (assumes normal distribution)


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
# Warmup Iteration   1: 5.802 ops/ms
# Warmup Iteration   2: 7.843 ops/ms
# Warmup Iteration   3: 8.068 ops/ms
Iteration   1: 8.110 ops/ms
Iteration   2: 8.238 ops/ms
Iteration   3: 8.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.169 ±(99.9%) 1.186 ops/ms [Average]
  (min, avg, max) = (8.110, 8.169, 8.238), stdev = 0.065
  CI (99.9%): [6.983, 9.355] (assumes normal distribution)


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
# Warmup Iteration   1: 4.472 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.002 ms/op
Iteration   1: 3.208 ±(99.9%) 0.003 ms/op
Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
Iteration   3: 3.128 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.138 ±(99.9%) 1.199 ms/op [Average]
  (min, avg, max) = (3.077, 3.138, 3.208), stdev = 0.066
  CI (99.9%): [1.939, 4.336] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.002 ms/op
Iteration   1: 2.956 ±(99.9%) 0.003 ms/op
Iteration   2: 2.892 ±(99.9%) 0.002 ms/op
Iteration   3: 2.801 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.883 ±(99.9%) 1.421 ms/op [Average]
  (min, avg, max) = (2.801, 2.883, 2.956), stdev = 0.078
  CI (99.9%): [1.462, 4.303] (assumes normal distribution)


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
# Warmup Iteration   1: 4.312 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.119 ±(99.9%) 0.002 ms/op
Iteration   2: 3.040 ±(99.9%) 0.004 ms/op
Iteration   3: 3.032 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.064 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (3.032, 3.064, 3.119), stdev = 0.048
  CI (99.9%): [2.186, 3.942] (assumes normal distribution)


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
# Warmup Iteration   1: 5.079 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.019 ms/op
Iteration   1: 4.001 ±(99.9%) 0.015 ms/op
Iteration   2: 4.086 ±(99.9%) 0.012 ms/op
Iteration   3: 4.038 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.042 ±(99.9%) 0.774 ms/op [Average]
  (min, avg, max) = (4.001, 4.042, 4.086), stdev = 0.042
  CI (99.9%): [3.267, 4.816] (assumes normal distribution)


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
# Warmup Iteration   1: 4.277 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  8.949 ms/op
                 createUser·p0.9999: 16.450 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 3.114 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  8.487 ms/op
                 createUser·p0.9999: 18.298 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.544 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  11.395 ms/op
                 createUser·p0.9999: 19.558 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306423
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13128 
    [ 2.500,  5.000) = 290985 
    [ 5.000,  7.500) = 1711 
    [ 7.500, 10.000) = 300 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      9.823 ms/op
     p(99.9900) =     18.505 ms/op
     p(99.9990) =     20.998 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.005 ms/op
Iteration   1: 2.962 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.573 ms/op
                 existUser·p0.999:  7.627 ms/op
                 existUser·p0.9999: 13.822 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   2: 3.100 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.743 ms/op
                 existUser·p0.999:  8.585 ms/op
                 existUser·p0.9999: 13.986 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.273 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.078 ms/op
                 existUser·p0.9999: 15.942 ms/op
                 existUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320074
  mean =      3.000 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1551 
    [ 1.250,  2.500) = 27801 
    [ 2.500,  3.750) = 275539 
    [ 3.750,  5.000) = 13078 
    [ 5.000,  6.250) = 983 
    [ 6.250,  7.500) = 709 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.273 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.913 ms/op
     p(99.9900) =     14.090 ms/op
     p(99.9990) =     15.958 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 4.506 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.063 ms/op
                 getUser·p0.999:  8.266 ms/op
                 getUser·p0.9999: 14.643 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  8.989 ms/op
                 getUser·p0.9999: 15.969 ms/op
                 getUser·p1.00:   16.466 ms/op

Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.149 ms/op
                 getUser·p0.999:  9.437 ms/op
                 getUser·p0.9999: 21.717 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306746
  mean =      3.128 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17574 
    [ 2.500,  5.000) = 285959 
    [ 5.000,  7.500) = 2658 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.046 ms/op
     p(99.9000) =      8.884 ms/op
     p(99.9900) =     18.033 ms/op
     p(99.9990) =     21.983 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 5.821 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.011 ms/op
Iteration   1: 3.925 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.704 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.969 ms/op
                 listUser·p0.9999: 15.445 ms/op
                 listUser·p1.00:   15.745 ms/op

Iteration   2: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   6.776 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 15.380 ms/op
                 listUser·p1.00:   16.318 ms/op

Iteration   3: 3.910 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  15.369 ms/op
                 listUser·p0.9999: 20.881 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246407
  mean =      3.896 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2767 
    [ 2.500,  5.000) = 227443 
    [ 5.000,  7.500) = 14937 
    [ 7.500, 10.000) = 718 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     19.279 ms/op
     p(99.9990) =     21.385 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.492 ± 3.256  ops/ms
ClientGrpc.existUser                       thrpt       3  10.782 ± 0.790  ops/ms
ClientGrpc.getUser                         thrpt       3  10.172 ± 1.962  ops/ms
ClientGrpc.listUser                        thrpt       3   8.169 ± 1.186  ops/ms
ClientGrpc.createUser                       avgt       3   3.138 ± 1.199   ms/op
ClientGrpc.existUser                        avgt       3   2.883 ± 1.421   ms/op
ClientGrpc.getUser                          avgt       3   3.064 ± 0.878   ms/op
ClientGrpc.listUser                         avgt       3   4.042 ± 0.774   ms/op
ClientGrpc.createUser                     sample  306423   3.134 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.544           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.823           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.505           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.135           ms/op
ClientGrpc.existUser                      sample  320074   3.000 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.273           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.913           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.090           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.155           ms/op
ClientGrpc.getUser                        sample  306746   3.128 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.715           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.965           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.046           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.884           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.033           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.118           ms/op
ClientGrpc.listUser                       sample  246407   3.896 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.977           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.107           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.279           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.496           ms/op
