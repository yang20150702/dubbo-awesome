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
# Warmup Iteration   1: 4.452 ops/ms
# Warmup Iteration   2: 9.982 ops/ms
# Warmup Iteration   3: 10.468 ops/ms
Iteration   1: 10.466 ops/ms
Iteration   2: 10.968 ops/ms
Iteration   3: 10.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.633 ±(99.9%) 5.290 ops/ms [Average]
  (min, avg, max) = (10.465, 10.633, 10.968), stdev = 0.290
  CI (99.9%): [5.343, 15.923] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.025 ops/ms
# Warmup Iteration   2: 11.053 ops/ms
# Warmup Iteration   3: 11.201 ops/ms
Iteration   1: 11.451 ops/ms
Iteration   2: 11.038 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.006 ±(99.9%) 8.421 ops/ms [Average]
  (min, avg, max) = (10.530, 11.006, 11.451), stdev = 0.462
  CI (99.9%): [2.586, 19.427] (assumes normal distribution)


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
# Warmup Iteration   1: 6.421 ops/ms
# Warmup Iteration   2: 10.334 ops/ms
# Warmup Iteration   3: 10.679 ops/ms
Iteration   1: 10.876 ops/ms
Iteration   2: 10.818 ops/ms
Iteration   3: 10.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.764 ±(99.9%) 2.670 ops/ms [Average]
  (min, avg, max) = (10.598, 10.764, 10.876), stdev = 0.146
  CI (99.9%): [8.094, 13.434] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.071 ops/ms
# Warmup Iteration   2: 7.968 ops/ms
# Warmup Iteration   3: 8.223 ops/ms
Iteration   1: 8.251 ops/ms
Iteration   2: 7.977 ops/ms
Iteration   3: 8.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.266 ±(99.9%) 5.417 ops/ms [Average]
  (min, avg, max) = (7.977, 8.266, 8.570), stdev = 0.297
  CI (99.9%): [2.849, 13.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.002 ms/op
Iteration   1: 3.077 ±(99.9%) 0.002 ms/op
Iteration   2: 3.211 ±(99.9%) 0.002 ms/op
Iteration   3: 3.175 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.154 ±(99.9%) 1.273 ms/op [Average]
  (min, avg, max) = (3.077, 3.154, 3.211), stdev = 0.070
  CI (99.9%): [1.881, 4.428] (assumes normal distribution)


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
# Warmup Iteration   1: 3.679 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.003 ms/op
Iteration   1: 3.065 ±(99.9%) 0.002 ms/op
Iteration   2: 3.029 ±(99.9%) 0.007 ms/op
Iteration   3: 2.997 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.030 ±(99.9%) 0.619 ms/op [Average]
  (min, avg, max) = (2.997, 3.030, 3.065), stdev = 0.034
  CI (99.9%): [2.411, 3.649] (assumes normal distribution)


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.002 ms/op
Iteration   1: 3.158 ±(99.9%) 0.002 ms/op
Iteration   2: 3.226 ±(99.9%) 0.002 ms/op
Iteration   3: 3.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.143 ±(99.9%) 1.672 ms/op [Average]
  (min, avg, max) = (3.044, 3.143, 3.226), stdev = 0.092
  CI (99.9%): [1.470, 4.815] (assumes normal distribution)


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
# Warmup Iteration   1: 5.082 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.024 ms/op
Iteration   1: 3.835 ±(99.9%) 0.013 ms/op
Iteration   2: 3.906 ±(99.9%) 0.034 ms/op
Iteration   3: 3.728 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.823 ±(99.9%) 1.637 ms/op [Average]
  (min, avg, max) = (3.728, 3.823, 3.906), stdev = 0.090
  CI (99.9%): [2.186, 5.460] (assumes normal distribution)


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.440 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.084 ms/op
                 createUser·p0.999:  7.032 ms/op
                 createUser·p0.9999: 14.991 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  6.373 ms/op
                 createUser·p0.9999: 16.905 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.137 ms/op
                 createUser·p0.999:  11.359 ms/op
                 createUser·p0.9999: 20.039 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319440
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44335 
    [ 2.500,  5.000) = 274266 
    [ 5.000,  7.500) = 477 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      8.696 ms/op
     p(99.9900) =     19.464 ms/op
     p(99.9990) =     20.310 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  4.833 ms/op
                 existUser·p0.9999: 18.776 ms/op
                 existUser·p1.00:   19.137 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  7.157 ms/op
                 existUser·p0.9999: 13.539 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   3: 2.778 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  7.135 ms/op
                 existUser·p0.9999: 15.760 ms/op
                 existUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326269
  mean =      2.943 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2319 
    [ 1.250,  2.500) = 54274 
    [ 2.500,  3.750) = 248683 
    [ 3.750,  5.000) = 20099 
    [ 5.000,  6.250) = 428 
    [ 6.250,  7.500) = 231 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      6.887 ms/op
     p(99.9900) =     16.870 ms/op
     p(99.9990) =     19.054 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
Iteration   1: 2.953 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  8.190 ms/op
                 getUser·p0.9999: 12.405 ms/op
                 getUser·p1.00:   12.714 ms/op

Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  6.742 ms/op
                 getUser·p0.9999: 14.680 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   3: 2.939 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.595 ms/op
                 getUser·p0.9999: 23.341 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323770
  mean =      2.964 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53666 
    [ 2.500,  5.000) = 269067 
    [ 5.000,  7.500) = 706 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.561 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     24.186 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 4.779 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.011 ms/op
Iteration   1: 4.044 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.749 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  13.696 ms/op
                 listUser·p0.9999: 22.098 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 3.991 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  16.003 ms/op
                 listUser·p0.9999: 24.739 ms/op
                 listUser·p1.00:   25.199 ms/op

Iteration   3: 4.052 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.854 ms/op
                 listUser·p0.999:  13.600 ms/op
                 listUser·p0.9999: 25.579 ms/op
                 listUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238102
  mean =      4.029 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2230 
    [ 2.500,  5.000) = 206656 
    [ 5.000,  7.500) = 27890 
    [ 7.500, 10.000) = 902 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     26.149 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.633 ± 5.290  ops/ms
ClientGrpc.existUser                       thrpt       3  11.006 ± 8.421  ops/ms
ClientGrpc.getUser                         thrpt       3  10.764 ± 2.670  ops/ms
ClientGrpc.listUser                        thrpt       3   8.266 ± 5.417  ops/ms
ClientGrpc.createUser                       avgt       3   3.154 ± 1.273   ms/op
ClientGrpc.existUser                        avgt       3   3.030 ± 0.619   ms/op
ClientGrpc.getUser                          avgt       3   3.143 ± 1.672   ms/op
ClientGrpc.listUser                         avgt       3   3.823 ± 1.637   ms/op
ClientGrpc.createUser                     sample  319440   3.006 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.440           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.153           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.696           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.464           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.775           ms/op
ClientGrpc.existUser                      sample  326269   2.943 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.536           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.887           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.870           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.137           ms/op
ClientGrpc.getUser                        sample  323770   2.964 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.744           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.561           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.807           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.838           ms/op
ClientGrpc.listUser                       sample  238102   4.029 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.749           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.926           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.478           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.739           ms/op
