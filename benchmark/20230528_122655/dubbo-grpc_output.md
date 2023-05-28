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
# Warmup Iteration   1: 4.239 ops/ms
# Warmup Iteration   2: 9.277 ops/ms
# Warmup Iteration   3: 10.012 ops/ms
Iteration   1: 10.438 ops/ms
Iteration   2: 10.612 ops/ms
Iteration   3: 10.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.521 ±(99.9%) 1.584 ops/ms [Average]
  (min, avg, max) = (10.438, 10.521, 10.612), stdev = 0.087
  CI (99.9%): [8.937, 12.105] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.388 ops/ms
# Warmup Iteration   2: 10.487 ops/ms
# Warmup Iteration   3: 11.024 ops/ms
Iteration   1: 10.969 ops/ms
Iteration   2: 11.040 ops/ms
Iteration   3: 11.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.008 ±(99.9%) 0.661 ops/ms [Average]
  (min, avg, max) = (10.969, 11.008, 11.040), stdev = 0.036
  CI (99.9%): [10.347, 11.669] (assumes normal distribution)


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
# Warmup Iteration   1: 7.196 ops/ms
# Warmup Iteration   2: 10.070 ops/ms
# Warmup Iteration   3: 10.398 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.412 ops/ms
Iteration   3: 10.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.441 ±(99.9%) 0.617 ops/ms [Average]
  (min, avg, max) = (10.412, 10.441, 10.478), stdev = 0.034
  CI (99.9%): [9.823, 11.058] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.335 ops/ms
# Warmup Iteration   2: 7.752 ops/ms
# Warmup Iteration   3: 8.020 ops/ms
Iteration   1: 7.968 ops/ms
Iteration   2: 8.063 ops/ms
Iteration   3: 8.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.031 ±(99.9%) 0.990 ops/ms [Average]
  (min, avg, max) = (7.968, 8.031, 8.063), stdev = 0.054
  CI (99.9%): [7.041, 9.021] (assumes normal distribution)


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.002 ms/op
Iteration   1: 3.004 ±(99.9%) 0.002 ms/op
Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
Iteration   3: 2.986 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.017 ±(99.9%) 0.707 ms/op [Average]
  (min, avg, max) = (2.986, 3.017, 3.061), stdev = 0.039
  CI (99.9%): [2.310, 3.725] (assumes normal distribution)


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.003 ms/op
Iteration   1: 2.891 ±(99.9%) 0.003 ms/op
Iteration   2: 2.878 ±(99.9%) 0.003 ms/op
Iteration   3: 2.888 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.886 ±(99.9%) 0.123 ms/op [Average]
  (min, avg, max) = (2.878, 2.886, 2.891), stdev = 0.007
  CI (99.9%): [2.763, 3.009] (assumes normal distribution)


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
# Warmup Iteration   1: 4.369 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.004 ms/op
Iteration   1: 3.063 ±(99.9%) 0.004 ms/op
Iteration   2: 3.008 ±(99.9%) 0.002 ms/op
Iteration   3: 3.003 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.025 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (3.003, 3.025, 3.063), stdev = 0.033
  CI (99.9%): [2.420, 3.629] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.697 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.012 ms/op
Iteration   1: 3.957 ±(99.9%) 0.014 ms/op
Iteration   2: 3.913 ±(99.9%) 0.028 ms/op
Iteration   3: 4.090 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.987 ±(99.9%) 1.680 ms/op [Average]
  (min, avg, max) = (3.913, 3.987, 4.090), stdev = 0.092
  CI (99.9%): [2.307, 5.666] (assumes normal distribution)


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
Iteration   1: 3.076 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.449 ms/op
                 createUser·p0.999:  6.988 ms/op
                 createUser·p0.9999: 16.577 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  7.954 ms/op
                 createUser·p0.9999: 18.088 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 19.890 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315429
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21375 
    [ 2.500,  5.000) = 292526 
    [ 5.000,  7.500) = 1216 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.443 ms/op
     p(99.9900) =     19.560 ms/op
     p(99.9990) =     21.292 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.005 ms/op
Iteration   1: 2.923 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  7.220 ms/op
                 existUser·p0.9999: 12.175 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   2: 2.881 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   3.865 ms/op
                 existUser·p0.999:  5.046 ms/op
                 existUser·p0.9999: 16.732 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   3: 2.923 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 16.321 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330156
  mean =      2.909 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 446 
    [ 1.250,  2.500) = 33360 
    [ 2.500,  3.750) = 289208 
    [ 3.750,  5.000) = 6384 
    [ 5.000,  6.250) = 235 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.502 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =      7.283 ms/op
     p(99.9900) =     16.302 ms/op
     p(99.9990) =     18.068 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
Iteration   1: 3.113 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  8.782 ms/op
                 getUser·p0.9999: 13.402 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   2: 3.030 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.073 ms/op
                 getUser·p0.9999: 13.835 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   3: 3.005 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.527 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.344 ms/op
                 getUser·p0.9999: 17.203 ms/op
                 getUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314739
  mean =      3.049 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 297 
    [ 1.250,  2.500) = 13935 
    [ 2.500,  3.750) = 285666 
    [ 3.750,  5.000) = 13340 
    [ 5.000,  6.250) = 781 
    [ 6.250,  7.500) = 392 
    [ 7.500,  8.750) = 97 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 146 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.633 ms/op
     p(99.9900) =     15.515 ms/op
     p(99.9990) =     17.231 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 4.868 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.011 ms/op
Iteration   1: 4.019 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.663 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 16.646 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   2: 4.065 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  15.838 ms/op
                 listUser·p0.9999: 23.560 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 4.047 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  21.494 ms/op
                 listUser·p0.9999: 27.895 ms/op
                 listUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237537
  mean =      4.043 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2412 
    [ 2.500,  5.000) = 210521 
    [ 5.000,  7.500) = 23160 
    [ 7.500, 10.000) = 1003 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     15.850 ms/op
     p(99.9900) =     26.886 ms/op
     p(99.9990) =     28.844 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.521 ± 1.584  ops/ms
ClientGrpc.existUser                       thrpt       3  11.008 ± 0.661  ops/ms
ClientGrpc.getUser                         thrpt       3  10.441 ± 0.617  ops/ms
ClientGrpc.listUser                        thrpt       3   8.031 ± 0.990  ops/ms
ClientGrpc.createUser                       avgt       3   3.017 ± 0.707   ms/op
ClientGrpc.existUser                        avgt       3   2.886 ± 0.123   ms/op
ClientGrpc.getUser                          avgt       3   3.025 ± 0.605   ms/op
ClientGrpc.listUser                         avgt       3   3.987 ± 1.680   ms/op
ClientGrpc.createUser                     sample  315429   3.043 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.663           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.443           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.560           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.430           ms/op
ClientGrpc.existUser                      sample  330156   2.909 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.578           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.047           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.283           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.302           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  314739   3.049 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.803           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.633           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.515           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.302           ms/op
ClientGrpc.listUser                       sample  237537   4.043 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.055           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.850           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.886           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.934           ms/op
